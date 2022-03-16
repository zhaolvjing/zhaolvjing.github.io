---
layout: post
tags: [GitHub Pages, Jekyll]
toc: true
---

## 建立 GitHub 仓库
仓库可以是自建的，也可以是 fork 别人的，区别点在于后续的一系列配置文件是自己新建还是直接改别人的，两种都可以。由于个人知识有限，而且搭建博客网站的初衷也是为了自己的笔记记录，所以为了快速上手，选择  fork 别人的主题仓库，免去一些繁琐的配置。仓库层面需要注意的点主要有以下两点：

* 仓库的名称格式：username.github.io
* Pages 设置：源、主题等

Jekyll主题库：[Jekyll Themes](http://jekyllthemes.org/)，可以挑选自己喜欢的主题

## Jekyll 构站环境准备
* Ruby：`ruby -v`（version 2.5.0 or higher）
* RubyGems：`gem -v`
* GCC and Make：`gcc -v`，`g++ -v`，`make -v`
* Jekyll：`jekyll -v`，如果没有安装，执行`sudo gem install jekyll

## Jekyll 配置文件简介
这里只列出几个比较关键的文件目录，其他的一些配置文件可参考别人的主题仓库进行理解。

* _layouts：存放页面模板，md 或 html 文件的内容会填充模板
* _posts：博客文章页面
* _config.yml：全局配置文件，具体的配置详情可参考 [Jekyll官方配置说明](https://jekyllrb.com/docs/configuration/)

## 其他资源
* [图标字体库](https://fontawesome.com/)：用于网站美化设计
