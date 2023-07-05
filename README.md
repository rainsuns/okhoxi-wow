everwar开源魔兽世界
==============================
> 魔兽世界是世界上最成功的游戏，这是一套完整的服务端源码版本。
2023年6月，官网已经正式发布。欢迎点赞收藏。

# overview
<a href="http://everwar.cn" target="_blank">everwar开源魔兽世界官网</a>
<br/>
```
everwar开源魔兽世界

顶级为60的魔兽世界版本是WOW最经典的版本,让我们重温经典吧。
觉得有用就赞一个，欢迎fork
https://github.com/geektcp/everwar.git

技术支持邮箱(直接把问题和期望写清楚)：
```
<karinpoky@163.com>

```
感谢各位的star，支持和关注，接下来这个项目也会进行持续的更新，大家可以留意动态。
2023年会发布一个新版本，基于CentOS7.x的版本，并部署到公网，到时候方便大家直接使用。
```

# feature
```
在git找到其他魔兽世界服务端项目基本上完全没法使用。
往往clone下来是编译不了的，总会有各种问题。而这个git项目工程没这问题。

本项目支持机器人，自己可以创建玩家组队进行游戏。
```

# branch
```
目前有3个分支：
master: 
主分支，默认是最新可用版本。
编译构建可用。
目前是基于CentOS6.5的可用版本，后续会更新到基于CentOS7.9的版本。

branch.CentOS7.9：
接下里的开发一个基于CentOS7.9的版本就在这个分支上进行。

branch.CentOS6.5：
存档分支，
这个分支的代码是基于CentOS6.5的完整的可用的分支版本，
编译构建可用。
永久固定是基于CentOS6.5的版本。
```

# client
```
魔兽世界经典旧世客户端下载地址:
https://pan.baidu.com/s/1BgIYpZEmfTiAmeD_lMB1Sg
```

# os
```
CentOS 6.5 下载地址：
https://vault.centos.org/6.5/isos/x86_64/

CentOS 7.9 下载地址：
https://ftp.riken.jp/Linux/centos/7.9.2009/isos/x86_64/

完整的二进制安装包下载地址(仅支持CentOS 6.5)：
https://github.com/geektcp/everwar/releases/tag/1.0

完整的二进制安装包下载地址(支持CentOS 7.9)：
待发布
```

# describe
```
魔兽世界的服务端虽然没有客户端那么笨重，但是服务端的逻辑是比较复杂的。纯C/C++代码大约50万行。
阅读并维护，二次开发这样一款经典游戏的服务端源码，也是一件非常有趣的事情。

这是一个基于portalclassic，优化部分代码后的二次开发版本。
客户端使用1.12.x版本(60魔兽经典客户端)
```

- 界面截图
![登录入口](https://github.com/geektcp/everwar/blob/master/doc/screen/login.png)

