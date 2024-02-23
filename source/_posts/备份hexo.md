---
title: 备份hexo
date: 2024-02-22 23:17:12
tags: hexo
categories: Knowledge
---

### 备份hexo

若项目部署在github上使用gitpage访问，可以在项目设置页面pages设置指定的分支，比如mastar分支用来部署博客
此时可以在创建一个分支hexo_source，用来存放源码

这样就实现了网站和源码的备份，即使本地的代码丢失，github上也有源码，重新clone一份就可以了
而且还方便了在不同地方进行写作，只需要每次写作前先pull一下源码即可。