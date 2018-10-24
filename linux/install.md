#### u盘制作工具
rufus
bios设置u盘启动
#### 18.04 版本的wifi问题
acer的电脑会有问题
1. 输入rfkill list 查看是否硬件被禁用
2. 如果硬件被禁用
sudo nano/etc/modprobe.d/blacklist.conf
将 blacklist acer_wmi 作为新行添加到这里文件的底部。
然后重启。
