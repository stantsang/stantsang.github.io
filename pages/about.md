---
layout: page
title: About
description: 打码改变世界
keywords: Stantsang, 星云志
comments: true
menu: 关于
permalink: /about/
---

我是星云志，码而生，码而立。

仰慕「优雅编码的艺术」。

## 坚信

* 熟能生巧
* 努力改变人生

## 联系

* GitHub：[@mzlogin](https://github.com/stantsang)
* 博客：[{{ site.title }}]({{ site.url }})
* 微博: [@mzlogin](http://weibo.com/mzlogin)

## Skill Keywords

#### Software Engineer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_software_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>

#### Mobile Developer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_mobile_app_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>

#### Windows Developer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_windows_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>
