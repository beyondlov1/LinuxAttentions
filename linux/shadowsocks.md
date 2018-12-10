#### install
sudo apt-get install python-pip
sudo pip install shadowsocks
下载elactronic-shadowsocks
ubuntu梗概网络连接中的代理模式
参考：https://www.jianshu.com/p/c3ee7b68a950

#### xfce+ubuntu+proxychains+electron-ssr
xfce 是一个非常快的linux桌面,但是没有gnome中默认的代理设置
所以要用proxychains来实现这个问题
首先,安装proxychains : sudo apt install proxychains
然后,进行配置: sudo nano /etc/proxychains.conf
将最后一行删掉, 改为: socks5 127.0.0.1 1080
之后启动用命令行来启动浏览器: proxychains google-chrome
完成
参考: http://www.cnblogs.com/angiebare/p/9356958.html

####ssr
https://ssr-panel.minirplus.com/
