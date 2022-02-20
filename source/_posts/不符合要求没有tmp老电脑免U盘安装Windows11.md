---
title: 不符合要求没有tmp老电脑免U盘安装Windows11
date: 2022-02-21 00:32:06
tags:
    -系统安装
categories:
    - 操作系统
    - Windows11
comments: true
---

&emsp;&emsp; Windows11发布正式版已经有一段时间了，但是要想升级到Windows11还有很多要求和限制不；Windows 11的最低硬件要求分为4点：1GH或者更快的64位处理器，双核以上CPU；4GB以上的运行内存，存储空间64GB起步；带有WDDM2.0驱动的DirectX 12以上显卡；主板支持TPM2.0安全芯片。

&emsp;&emsp; 我通过谷歌和YouTube还是找到了很多解决办法，大部分方法也可以安装但是非常麻烦，我通总结经验发现了最优解决方案，下面我来说一下我的解决办法`不要U盘` 只要下载一个Windows11ISO文件就可以了。

<escape><!-- more --></escape>

## 下载Windows11 ISO文件镜像文件
1.  进入[微软网站](https://www.microsoft.com/zh-cn/software-download/windows11/)

2. 下载ISO镜像文件
> 下面我放出的是64位简体中文下载地址

<https://software-download.microsoft.com/sg/Win11_Chinese(Simplified)_x64v1.iso?t=afca7fc6-48a6-4be3-9852-9e483018dbb4&e=1645462607&h=82608bb6fecebcaf65250234d27a5700>

## 使用压缩软件解压文件
这一步这里就不多说了。

## 删除替换文件
> 进入已经解压缩的Windows11文件夹找到sources文件夹然后找到`appraiserres.dll`文件复制文件名然后删除这个文件，然后新建一个文件夹把这个文件夹重命名粘贴之前复制文件名即可。
如图
![](https://goindex.pzb.workers.dev/0:/屏幕截图(4).png)

## 安装
>返回上一级文件点击安装程序开始傻瓜式的安装，Windows11安装必须要用网络和微软账号，然后就可以体验Windows11了。
