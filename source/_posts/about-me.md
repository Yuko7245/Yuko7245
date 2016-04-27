---
title: about me
date: 2016-04-27 15:43:29
tags:
---


系统环境配置

要使用Hexo，需要在你的系统中支持Nodejs以及Git，如果还没有，那就开始安装吧！

安装Node.js
下载Node.js
参考地址：安装Node.js

安装Git
下载地址：http://git-scm.com/download/

安装Hexo
$ cd d:/hexo
$ npm install hexo-cli -g
$ hexo init blog
$ cd blog
$ npm install
$ hexo g # 或者hexo generate
$ hexo s # 或者hexo server，可以在http://localhost:4000/ 查看
这里有必要提下Hexo常用的几个命令：

hexo generate (hexo g) 生成静态文件，会在当前目录下生成一个新的叫做public的文件夹
hexo server (hexo s) 启动本地web服务，用于博客的预览
hexo deploy (hexo d) 部署播客到远端（比如github, heroku等平台）
另外还有其他几个常用命令：