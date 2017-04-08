---
layout: page
title: About
description: 打码改变世界
keywords: Yanyao Shen
comments: true
menu: 关于
permalink: /about/
---

> My name is Yanyao Shen, I am interested in understanding the core techniques of machine learning that provides the foundation to solve useful problems. 

## Contact

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
