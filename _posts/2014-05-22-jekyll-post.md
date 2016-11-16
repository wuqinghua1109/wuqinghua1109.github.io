---
layout: post
title: "jekyll搭建"
date: 2014-5-22
excerpt: "jekyll搭建"
tags: [sample post, readability, test]
comments: true
---

* ruby安装
* devkit安装
* jekyll搭建

## Ruby安装包下载
   到Ruby官网下载对应系统版本的安装包
   我下载使用window 8 64对应安装包
   rubyinstaller-2.3.1-x64.exe；


   安装Ruby
   双击rubyinstaller-2.2.3-x64.exe开始安装：
   1、选择安装语言，这里只有英文和日语；
   2、勾选“I accept the License“,同意协议；
   3、选择安装路径，我们不要安装在有空格或者中文名称的目录下，记得勾选”Add Ruby executables to your PATH“,这样安装成功之后就可以，让任意目录下执行命令；
   最后等待安装

   检查是否安装成功win+r输入cmd回车打开终端输入ruby -v； 
   $ ruby -v
   ruby 2.3.1p112 (2016-04-26 revision 54768) [x64-mingw32]
   显示版本信息说明安装成功
   devkit安装
   

## jekyll搭建
   通过Gem获取Jekyll模板 
   $ gem install jekyll -v "3.0.1"
   安装成功，最后会有” gems installed“输出；


## jekyll  生成静态页面并访问
   生成静态页面
   jekyll new myblog
   启动服务
   $ cd myblog/
   $ jekyll server
   访问站点
   http://127.0.0.1:4000/

## 卸载jekyll 
   $ gem uninstall jekyll