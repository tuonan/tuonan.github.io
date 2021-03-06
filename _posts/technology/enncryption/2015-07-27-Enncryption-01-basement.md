---
layout: post
title:  加密算法(一) - 基础
date:   2015-07-27 22:17:00 +0800
categories: 技术文档
tag: 加密算法
---

* content
{:toc}


> 柯克霍夫原则：数据的安全基于密钥而不是算法的保密。即系统的安全取决于密钥，对密钥保密，对算法公开。--现代密码学设计的基本原则

---

密码分类
=================================

时间分类
------------------------------------

古典密码：以字符为基本加密单元

现代密码：以信息块为基本加密单元

保密内容分类
------------------------------------

受限制算法：算法的保密性基于保持算法的秘密

基于密钥算法：算法的保密性基于对密钥的保密

密码体制
------------------------------------

对称密码：指加密密钥和解密密钥相同

非对称密码：指加密密钥和解密密钥不同，密钥分公钥和私钥

明文处理方法
------------------------------------

分组密码：指加密时将明文分成固定长度的组，用同一密钥和算法对每一块加密，输出也是固定长度的密文。多用于网络加密

流密码：也称序列密码。指加密时每次加密一位或者一个字节明文

散列函数
------------------------------------

散列函数用来验证数据的完整性

* 长度不受限制
* 哈希值容易计算
* 散列运算过程不可逆
* MD5, SHA, MAC

<br />
<br />

参考资料
===========================

[慕课网-Java实现Base64加密](http://www.imooc.com/learn/285)

<br />
<br />
