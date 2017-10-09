---
layout: post
title: "IDEA启动卡顿"
categories: [IDEA]
description: 解决idea启动慢的问题
keywords:
---

### IDEA启动卡顿

近来每次启动idea都需要一分钟以上，并且启动后索引操作也很慢，究其原因是idea分配的推内存太小

打开idea安装目录下的idea.exe.vmoptions文件，修改里面的-Xms（初始堆大小）和-Xmx（最大堆大小）属性，比如像下面：


>　　-Xms1024m
>
>　　-Xmx2048m
>
