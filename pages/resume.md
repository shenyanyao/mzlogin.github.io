---
layout: page
title: Links
description: 没有链接的博客是孤独的
keywords: 友情链接
comments: true
menu: 链接
permalink: /resume/
---

## About Me
> Hi, I am Yanyao, a second year Ph.D. student at Electrical and Computer Engineering, University of Texas at Austin. 

>I am fortunate to have Prof. Sujay Sanghavi to be my advisor. Before coming to UT, I got my Bachelor Degree from Tsinghua University in China, majored in Electronics and Electrical Engineering. My current research interest widely lies in the field of machine learning, statistical learning theory, and artificial intelligence.

> My goal is to design algorithms that can significantly improve the performance in real applications with solid theoretic understanding of the algorithm and its performance.

## Publications

> Y.Shen, Q.Huang, N.Srebro, S.Sanghavi,"Normalized Spectral Map Synchronization",  NIPS, 2016.

> L.Xu, C.Jiang, Y.Shen, T.Q.S.Quek, Z.Han, Y.Ren. "Energy Efficient D2D Communications: a Perspective of Mechanism Design." IEEE Trans. on Wireless Communs., accepted.

> Y.Shen, C.Jiang, T.Q.S.Quek, H.Zhang, Y.Ren. "Pricing equilibrium for data redistribution market in wireless networks with matching methodology." IEEE ICC, 2015, pp. 3051-3056. IEEE, 2015.

> Y.Shen C.Jiang, T.Q.S.Quek, Y.Ren. "Device-to-Device-Assisted Communications in Cellular Networks: An Energy Efficient Approach in Downlink Video Sharing Scenario." IEEE Trans. on Wireless Communs. 15, no. 2 (2016): 1575-1587.
 
> Y.Shen, C.Jiang, T.Q.S.Quek, Y.Ren. "Location-aware device communication design: exploration and exploitation on energy." IEEE Wireless Communs. 23, no. 2 (2016): 46-52.

> Y.Shen, C.Jiang, T.Q.S.Quek, H.Zhang, Y.Ren. "Device-to-device cluster assisted downlink video sharing—A base station energy saving approach." IEEE GlobalSIP, 2014, pp. 108-112. IEEE, 2014.

## Core Courses
### Undergraduate Level<br />
> Signals and Systems (98/100, 1st/20) <br />

> Calculus (100/100, 1st/130)<br />

> Data Structure and Algorithms (93/100, 2nd/100)<br />

> Linear Algebra (98/100)<br />

> Computer Networks<br />

> Programming Language (C++, Matlab)<br />

### Graduate Level <br />
> Probability and Stochastic Processes (raw score 99.02%) <br />

> Large-Scale Machine Learning<br />

> Algorithms: Techniques & Theory<br />

> Convex Optimization<br />

> Deep Learning<br />

> Sublinear Algorithm<br />

> Estimation Theory<br />

> Nonlinear Function Analysis<br />

> Digital Signal Processing<br />

### Teaching Assistance <br />
> Fall 2015 & Spring 2016: Teaching Assistant for EE351K: Probability and Random Processes.<br />

## Selected Honors
>2016.04 CapitalOne Modelling Competition, Final round 2nd place<br />

>2015.06 Outstanding Graduates, Tsinghua University <br />

>2015.06 Outstanding Graduation Thesis in EE Department, Tsinghua University<br />

>2013.10 National Scholarship, Tsinghua University<br />

>2012.10 National Scholarship, Tsinghua University <br />

>2013.09 Special Prize (Highest) in the 13th “Challenge Cup” National Contest of College Students’ Scientific and Technological Work, Beijing Division (Less than 1‰)<br />

{% for link in site.data.links %}
* [{{ link.name }}]({{ link.url }})
{% endfor %}
