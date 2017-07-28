# way-to-use-GitHub

[关于Git的优点的简介，对add、commit、branch等命令的介绍](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/00137396287703354d8c6c01c904c7d9ff056ae23da865a000)


# Command

- ssh username@host_ip_or_name
> 登陆服务器（咱的服务器用的是Linux，于是就在命令行中用Linux的命令操作服务器工作就行）

- exit
> 登出服务器

- pwd  // print working directory
> 显示当前目录

- mkdir filename  // make directory
> 在当前目录下创建一个空文件夹

- cd pathname  // change directory
> 进入指定目录

> // cd ../ (返回上一级目录)

- git init
> 在当前目录中创建Git仓库（会生成一个.git隐藏文件夹）
  
  
  
    
    
- git remote
> 不带参数，列出已经存在的远程分支

- git remote add origin [url] (username@host_ip_or_name:filepath/filename.git) [1](http://blog.csdn.net/w13770269691/article/details/38704941) [2](http://blog.csdn.net/u010412719/article/details/72860193) 
> 创建名为origin的remote分支，链接指向url

- git remote set-url origin [url]
> Update the URL

- git remote remove [name]
> 删除指定的remote分支

- git push (-u) origin master
> 提交本地分支到远程仓库( on your first push, you may want to add the -u parameter (i.e. git push -u origin master) if you want master in that repository to be your default upstream for your master)


