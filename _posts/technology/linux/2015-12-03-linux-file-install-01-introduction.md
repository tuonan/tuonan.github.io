---
layout: post
title:  Linux环境下的文件安装之(一) - 软件包管理简介
date:   2015-12-03 23:13:00 +0800
categories: 技术文档
tag: Linux
---

* content
{:toc}


软件包分类
=================================

源码包
---------------------------------

+ 优点:
	+ 开源，如果有足够的能力，可以修改源代码
	+ 可以自由选择所需的功能
	+ 软件是编译安装，所以更加适合自己的系统，更加稳定也效率更高
	+ 卸载方便

+ 缺点:
	+ 安装过程步骤较多，尤其安装较大的软件集合时(如LAMP环境)，容易出现拼写错误
	+ 编译过程时间较长，安装比二进制安装时间长
	+ 因为是编译安装，安装过程中一旦报错，新手很难解决

+ 脚本安装包：就是把复杂的软件包安装过程写成了程序脚本，初学者可以执行程序脚本实现一键安装。但实际安装的还是源码包和二进制包
	+ 优点是安装简单快捷
	+ 缺点是完全丧失了自定义性

二进制包（RPM包，系统默认包）
---------------------------------

+ 优点:
	+ 包管理系统简单，只通过几个命令就可以实现包的安装，升级，查询和卸载
	+ 安装速度比源码包安装快很多

+ 缺点：
	+ 经过编译，不再可以看到源代码
	+ 功能选择不如源码包灵活
	+ 依赖性

<br />
<br />

参考资料：
===========================

慕课网-Linux软件安装管理：[http://www.imooc.com/learn/447](http://www.imooc.com/learn/447)

鸟哥的Linux私房菜: [http://linux.vbird.org/linux_server/0440ntp.php](http://linux.vbird.org/linux_server/0440ntp.php)

<br />
<br />