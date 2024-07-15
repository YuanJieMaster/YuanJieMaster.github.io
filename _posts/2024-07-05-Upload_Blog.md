---
layout: post
title: "搭建博客"
author: "YuanJie"
header-style: text
catalog: true
tags:
  - 单片机
  - stm32
---

 **·** Github Pages 搭建个人博客
===

省流：利用一个仓库搭建博客

传统方法搭建一个网站比较繁琐，需要在服务器上运行Web程序，还要购买域名和配置SSL证书，Github Pages提供了方便的搭建个人博客的方法

在github上创建一个专门的仓库，命名时固定的格式：https://用户名.github.io/ 例如我的博客：https://yuanjiemaster.github.io/

这里偷个懒，将别人的博客仓库folk过来然后进行修改

点击Settings-Pages-Deploy from a branch-Github Actions

选择Jekyll框架^生成一个Gibhub Actions^可以渲染markdown文件

然后以后只需要将markdown文件上传即可



 **·**  Jekyll 框架是什么？
---

一个简单易用的静态网站生成器，支持Markdown，集成Github Pages



 **·**  Github Actions 是什么？
---

github提供各种虚拟机，可以对程序进行各种自动化行为

