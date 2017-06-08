---
layout: page
title: About Me
description: write for someone called xiaohe
keywords: xiaohe
comments: true
menu: 关于我
permalink: /about/
---

I am ...

## 坚信

* Continuous Learning
* 你获得的回报跟你创造的价值正相关
* 代码改变世界

## 联系我

* GitHub：<https://github.com/xiaohe9569>
* 博客：[{{ site.title }}]({{ site.url }})
* 知乎: 

## Skill Keywords

#### Software Language Keywords
<div class="btn-inline">
    {% for keyword in site.skill_language_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>

#### Web Developer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_web_app_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>
