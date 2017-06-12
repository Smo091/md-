# ssh
### ssh介绍
 SSH是一种网络协议，用于计算机之间的加密登录
### git生成公钥和私钥
    + 命令:`ssh-keygen -t rsa`生成的公钥与私钥文件会在当用户目录的.ssh目录下.
### 具体操作步骤
  + 找到ssh文件夹里的id_rsa.pub文件，复制内容，单击github用户头像，选择setting→ssh and gpgkeys，在key里粘贴内容。
  
### 使用方法
   + 在github中创建一个空库，协议使用ssh协议。
   + 在本地建立一个库，add保存，commit提交，push到对应的库（记得写上对应的分支）
   + push的库的网址是在线的库的网址。
   
  
