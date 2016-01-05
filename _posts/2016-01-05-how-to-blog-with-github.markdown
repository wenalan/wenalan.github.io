---
layout: post
title:  "如何用github来写博客"
date:   2016-01-05 20:36:49 +0800
categories: 备忘
---

总体概念
通过在github上创建特定名称的repository，然后启动git pages功能，就能将其中的特定文件转化为博客了

最基本的要求
github账号，然后进行相关设置就可以了
之后，在repository中按照jekyll要求的目录结构，将文章放入_post目录即可


如果需要本地测试，那么需要安装一大堆东西
ruby（用于运行jekyll）
gem（用于安装jekyll）
python2（用于运行一个语法高亮控件）
pip（用于安装语法高亮组件）
git（用于同步本地文档和服务器文档）

这样在本地能够通过127.0.0.1:4000查看页面，没问题以后，再上传到公网
