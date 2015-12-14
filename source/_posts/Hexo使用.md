layout: '[layout]'
title: hexo使用心得
date: 2015-09-06 11:46:53
tags: Hexo
categories: 杂谈
---
  # HEXO 安装 #

 网上很多介绍安装hexo的文章 我是参照这位仁兄的博客来配置的，有需要的朋友可以去看看，写的挺详细的[http://ibruce.info/2013/11/22/hexo-your-blog/](http://ibruce.info/2013/11/22/hexo-your-blog/)

 # NEXT主题配置 #

 个人比较喜欢next主题,简洁大方,还有支持文档，[http://theme-next.iissnan.com/](http://theme-next.iissnan.com/)各种配置文档都有详细说明，可以省去很多事。
 
 #hexo常用命令#

hexo new "postName" #新建文章

hexo new page "pageName" #新建页面

hexo generate #生成静态页面至public目录

hexo server #开启预览访问端口（默认端口4000，'ctrl + c'关闭server）

hexo deploy #将.deploy目录部署到GitHub 

简写：

hexo n == hexo new

hexo g == hexo generate

hexo s == hexo server

hexo d == hexo deploy

 # 总结 #

 自己捣鼓了几天才把这个博客搭建出来,遇到最主要的问题是github pages 域名绑定问题，困恼了我几天,不过功夫不负有心人，经过查资料，多次尝试终于搞定。

