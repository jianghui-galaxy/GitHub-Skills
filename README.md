# GitHub-Skills

## 1.如何配置Linux Shell提交代码时默认用户和密码？

  （1）在指定的用户目录下，右键打开git bash 执行 命名：`ssh-agent bash` 

  （2）生成RSA密钥，执行命令：`ssh-keygen -t rsa -C xxxx@xxxx.com` 

  （3）添加密钥到ssh，执行的命令：`ssh-add` 

  （4）把公钥添加到Github:  点击头像---Settings---SSH and GPG keys---New SSH keys 写好Title，把上面生成的id_rsa.pub内容复制到Key下面的输入框中

  （5）在本地Linux Shell目录  `git remote -v` 

  （6）如果当前是https的，那么可以通过如下命令修改为ssh`git remote set-url origin git@github.com:jianghui-galaxy/Blogs.git`  

## 2.

