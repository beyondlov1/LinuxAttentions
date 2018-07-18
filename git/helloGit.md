如何使用git
1. 安装git：
sudo apt-get install git/git-core
2. 连接github：
- 创建一个文件夹，放项目
- 配置全局的变量：
git config --global user.name = "用户名或者用户ID"
git config --global user.email = "邮箱"
（等号两边要有空格）
- 创建密钥:
ssh-keygen -C 'you email address@gmail.com' -t rsa
- 上传公钥:
在github的account界面中找到SSH Public Key，添加。将生成的id_rsa.pub中的内容复制进去
- 之后在github上新建一个仓库，按显示的第一个代码来写就能添加第一个文件了,(要在新建的文件夹中init，然后会生成一个隐藏的.git文件)
3. 
- echo "# LinuxAttentions" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:beyondlov1/LinuxAttentions.git
git push -u origin master

- git remote add origin git@github.com:beyondlov1/LinuxAttentions.git
git push -u origin master

**Attention!!!**
要在空的文件夾中創建倉庫,不然會把以前的文件都刪除

reference: http://www.cnblogs.com/cocowool/archive/2010/10/19/1855616.html
