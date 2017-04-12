---
layout: page
title: About
description: 打码改变世界
keywords: Yanyao Shen
comments: true
menu: 关于
permalink: /about/
---
## About Me
> Hi, I am Yanyao, a second year Ph.D. student at Electrical and Computer Engineering, University of Texas at Austin. 

> I am fortunate to have Prof. Sujay Sanghavi to be my advisor. Before coming to UT, I got my Bachelor Degree from Tsinghua University in China, majored in Electronics and Electrical Engineering. My current research interest widely lies in the field of machine learning, statistical learning theory, and artificial intelligence.

> The need for good algorithms is exploding in many fields of our world. Understanding the mechanism of the algorithms, as well as their requirement, pros and cons, is the cornerstone of designing more advanced algorithms targeting on different applications. I am interested in designing those algorithms that can significantly improve the performance in present-day challenging applications with solid theoretic understanding of the algorithm and its performance. 

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
