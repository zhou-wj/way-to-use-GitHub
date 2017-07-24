# way-to-use-GitHub

[关于Git的优点的简介，对add、commit、branch等命令的介绍](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/00137396287703354d8c6c01c904c7d9ff056ae23da865a000)


# Command

- ssh username@host_ip_or_name
> 登陆服务器（咱的服务器用的是Linux，于是就在命令行中用Linux的命令操作服务器工作就行）

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

- git remote add origin [url]
> 创建名为origin的remote分支，链接指向url

- git remote remove [name]
> 删除指定的remote分支


