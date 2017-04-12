---
layout: page
title: Links
description: 没有链接的博客是孤独的
keywords: 友情链接
comments: true
menu: 链接
permalink: /resume/
---
> Get pdf version of my resume <a href="../file/cvYanyao201612v4.pdf"
   download="yanyaoCV.pdf">here</a>. 

## Education

<ul>
  <li>University of Texas at Austin</li>
  <ul>
    <li>2015.08 -- now. PhD candidate in Electrical and Computer Engineering</li>
    <ul>
    <li>GPA: 4.00/4.00</li>
    </ul>
  </ul>
  <li>Tsinghua University</li>
  <ul>
    <li>2011.09 -- 2015.07 Bachelor of Engineering in Electronic Engineering</li>
    <ul><li> GPA: 92/100</li></ul>
    <li>2012.09 -- 2015.07 Second Bachelor's Degree in School of Economics and Management</li>
  </ul>
</ul> 

## Publications
<ul>
<li><strong>Y.Shen</strong>, Q.Huang, N.Srebro, S.Sanghavi,"Normalized Spectral Map Synchronization",  NIPS, 2016.</li>

<li>L.Xu, C.Jiang, <strong>Y.Shen</strong>, T.Q.S.Quek, Z.Han, Y.Ren. "Energy Efficient D2D Communications: a Perspective of Mechanism Design." IEEE Trans. on Wireless Communs., accepted.</li>

<li><strong>Y.Shen</strong>, C.Jiang, T.Q.S.Quek, H.Zhang, Y.Ren. "Pricing equilibrium for data redistribution market in wireless networks with matching methodology." IEEE ICC, 2015, pp. 3051-3056. IEEE, 2015.</li>

<li><strong>Y.Shen</strong>, C.Jiang, T.Q.S.Quek, Y.Ren. "Device-to-Device-Assisted Communications in Cellular Networks: An Energy Efficient Approach in Downlink Video Sharing Scenario." IEEE Trans. on Wireless Communs. 15, no. 2 (2016): 1575-1587.</li>
 
<li><strong>Y.Shen</strong>, C.Jiang, T.Q.S.Quek, Y.Ren. "Location-aware device communication design: exploration and exploitation on energy." IEEE Wireless Communs. 23, no. 2 (2016): 46-52.</li>

<li><strong>Y.Shen</strong>, C.Jiang, T.Q.S.Quek, H.Zhang, Y.Ren. "Device-to-device cluster assisted downlink video sharing—A base station energy saving approach." IEEE GlobalSIP, 2014, pp. 108-112. IEEE, 2014.</li>
</ul>

## Projects
<ul>
  <li><strong>Guaranteed Nonconvex Optimization Algorithm -- with Application to Image Feature Points Matching</strong></li>
  <ul>
    <li>Research Assistant, 2015.10 -- 2016.09</li>
    <li>Inconsistency widely exist in computer vision domain which makes machine less intelligent. Spectral methods perform well in practice, dealing with the noise from incorrect correspondences. However, to the best of our knowledge, <strong>no prior work provide reasonable theoretic guarantee for the algorithm</strong>. In this project, we assume that we are only able to exploit noisy feature mapping, and the goal is to recover the ground truth. We propose a normalized spectral method which is a variant of power method, and is both efficient and robust. Moreover, our novel contribution is analyzing the random permutation noise and \textbf{prove the convergence and optimality of the algorithm}. Our paper was accepted by <strong>NIPS</strong>, 2016. </li>
  </ul>

  <li><strong>Deep Learning Projects</strong></li>
  <ul>
    <li>Team Leader (Course Project), 2016.08 -- 2016.11</li>
    <li>In the first project, we use a Yearbook dataset (consists of graduation grayscale photos) and try to predict the year a photo was taken. Our model provides a 4.2 years prediction error on average. Implementation is based on Tensorflow.</li>
    <li>In the second project, I tried to do objects direction recognition using 3D models. The motivation of this project is that current image understanding does not include richer information such as the direction of objects (In some circumstances, the direction of an object you see can make a big difference). To explore this scenario information, I collected a small dataset consists of calibrated 3D models. With deep convolution network, the result shows there exists some generalization performance to natural images qualitatively, and the trained model can generalize to unseen 3D models quantitatively.(More to explore in this area.)</li>
  </ul>

  <li><strong>Fraud Detection Modeling Competition (CapitalOne)</strong></li>
  <ul>
    <li>Team Leader, 2016.02 -- 2016.04</li>
    <li>Detecting fraud behavior is the key of analyzing credit card behavior and ensures customer satisfaction. In order to tackle this problem, we design a fraud detection model for large dataset with feature engineering and make evaluations. More specifically, we design three characteristic models based on fraud behavior and use algorithms including gradient boosted trees, logistic regression to generate predictions. We get <strong>2nd place</strong> in overall performance.</li>
  </ul>

  <li><strong>A Projector Interactive System Based on Structured Light</strong></li>
  <ul>
    <li>Team Leader, 2012.09 -- 2013.05</li>
    <li>Gesture interaction simplifies the way we communicate, and simplifying the procedure machines decoding the gesture information is important. Using only RGB images without depth information, an online gesture capturing algorithm was designed and implemented in a projector interactive system using C++ (OpenCV), where efficiency of the algorithm is due to the careful design of detecting method based on structured light. We gave demo presentation and won <strong>a special prize</strong> in Beijing division.</li>
  </ul>
</ul>

## Selected Honors
<ul>
<li>2016.04 CapitalOne Modelling Competition, Final round 2nd place</li>

<li>2015.06 Outstanding Graduates, Tsinghua University </li>

<li>2015.06 Outstanding Graduation Thesis in EE Department, Tsinghua University</li>

<li>2013.10 National Scholarship, Tsinghua University</li>

<li>2012.10 National Scholarship, Tsinghua University </li>

<li>2013.09 Special Prize (Highest) in the 13th “Challenge Cup” National Contest of College Students’ Scientific and Technological Work, Beijing Division (Less than 1‰)</li>
</ul>

## Core Courses
### Graduate Level 
<ul>
<li>Probability and Stochastic Processes (raw score 99.02%) </li>

<li>Large-Scale Machine Learning </li>

<li>Algorithms: Techniques & Theory </li>

<li>Convex Optimization </li>

<li>Deep Learning </li>

<li>Sublinear Algorithm </li>

<li>Estimation Theory </li>

<li>Nonlinear Function Analysis </li>

<li>Digital Signal Processing </li>
</ul>
### Teaching Assistance <br />
<ul>
<li>Fall 2015 & Spring 2016: Teaching Assistant for EE351K: Probability and Random Processes.</li>
</ul>
{% for link in site.data.links %}
* [{{ link.name }}]({{ link.url }})
{% endfor %}
