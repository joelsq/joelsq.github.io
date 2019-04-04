---
title: 搭建博客Github+jekyll+Writer
layout: post
categories: Blog
tags: jekyll
---
> 找完工作，剩下答辩和一些杂务，终于有时间做之前想做的事。以后会走程序员这条路，希望用一个博客来记录和督促自己。

## 环境
    Win8.1  

## 基本流程
两条路线均可，笔者觉得如果喜欢使用Jekyll Writer，可以选择第一条避坑。
1. 创建Github账号->安装配置Jekyll->使用Jekyll Writer->开始博客
2. 创建Github账号->安装配置Jekyll->创建博客仓库->使用Jekyll Writer->开始博客

主要介绍第一条的配置方法。

## 创建Github账号
[官网](https://github.com)注册即可。

## 安装配置Jekyll
Windows下安装Ruby建议使用__RubyInstaller.__  
以下这篇教程十分详细地介绍了__Windows下的Jekyll安装__，完美避坑。这里不再赘述。  
[Jekyll、MSYS2、Vibora 及在 Windows 下用 Linux](https://kaffa.im/jekyll-msys2-vibora-and-use-linux-on-windows.html)  

## 使用Jekyll Writer编写博客
Jekyll Writer是Jekyll官方提供的博客编辑器。  
个人觉得Jekyll Writer界面比较美观简洁，并且提供Github账户、仓库关联。  
[Jekyll Writer下载地址](http://jekyllwriter.com/)

* 解压后即可使用。
* 配置Github账号  
<img src="https://github.com/joelsq/joelsq.github.io/raw/master/img/buildBlog-sett_account.png" width = "70%" height = "70%" alt="配置Github账号" align=center />  
* 点击`Create new token`，创建token  
token description不重复即可

* 添加账户后，创建仓库  
__什么都不输入就创建__则是默认仓库，仓库名为`你的账户名.github.io`  
 <img src="https://github.com/joelsq/joelsq.github.io/raw/master/img/buildBolg-new-resp.png" width = "70%" height = "70%" alt="配置Github账号" align=center />  
 
* （选做）选择博客主题
jekyll writer上有Account->Theme选项，但可能网络问题无法打开在线主题，  
建议在Github的仓库__Settings__中找到GitHub Page，Choose a theme即可。
