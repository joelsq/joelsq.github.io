---
title: 搭建博客Github+jekyll+Writer
layout: post
categories: document
tags: 教程
---
* content
{:toc}



> 找完工作，剩下答辩和一些杂务，终于有时间做之前想做的事。  
> 以后会走程序员这条路，希望用一个博客来记录和督促自己。    

## 前言  
环境Win8.1，喜欢尽可能简约的方法，文末有较为详细的其他方法。


## 基本流程  
两条路线均可，笔者觉得如果喜欢使用Jekyll Writer，可以选择第一条避坑。
1. 创建Github账号->安装配置Jekyll（本地调试才需要）->使用Jekyll Writer->开始博客
2. 创建Github账号->安装配置Jekyll（本地调试才需要）->创建博客仓库->使用Jekyll Writer->开始博客

主要介绍第一条的配置方法。

### 创建Github账号  
 
[官网注册](https://github.com/)  

### 安装配置Jekyll  

* 若不需要本地运行jekyll来调试博客，这步可省略。  
但后期博客变复杂或者想设计得精美一点，最好有本地调试。  

* Windows下安装Ruby建议使用**RubyInstaller**  
以下这篇教程十分详细地介绍了**Windows下的Jekyll安装**，完美避坑。这里不再赘述。  
[Jekyll、MSYS2、Vibora 及在 Windows 下用 Linux](https://kaffa.im/jekyll-msys2-vibora-and-use-linux-on-windows.html)  

### 使用Jekyll Writer编写博客    
Jekyll Writer是Jekyll官方提供的博客编辑器。

* 优点：界面比较美观简洁，并且提供Github账户、仓库定Markdown基础较好
* 缺点：无法同步预览Markdown结果
* [Jekyll Writer下载地址](http://jekyllwriter.com/)    
* [Jekyll Writer 详细使用方法](https://sdk.cn/news/3811)  

![jekyll Writer主面板](https://github.com/joelsq/joelsq.github.io/raw/master/styles/images/buildBlog/buildBlog-why-jekyllWriter.png)  


1. 解压后即可使用.  
2. 配置Github账号  
![配置Github账号](https://github.com/joelsq/joelsq.github.io/raw/master/styles/images/buildBlog/buildBlog-sett_account.png)
3. 点击`Create new token`，创建token  
token description不重复即可
4. 添加账户后，创建仓库  
**什么都不输入就创建**则是默认仓库，仓库名为`你的账户名.github.io`  
![创建仓库](https://github.com/joelsq/joelsq.github.io/raw/master/styles/images/buildBlog/buildBolg-new-resp.png)
5.（选）选择博客主题  
jekyll writer上有Account->Theme选项，但可能网络问题无法打开在线主题，   
[如何替换主题](https://www.jianshu.com/p/da1287bc7874)


## 相关参考  
* [搭建Github Pages个人博客网站](https://blog.csdn.net/KNIGH_YUN/article/details/79774344#6)  
* [利用 GitHub Pages 快速搭建个人博客](https://www.jianshu.com/p/e68fba58f75c)  
* [jekyll 中文文档](https://www.jekyll.com.cn/docs/structe/)