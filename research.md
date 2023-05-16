---
layout: work
title: Research
slug: /research
items:
  - title: My Interest 1
    image:
      src: /assets/img/work/p1.jpg
      alt: water
    description: Inspired by <a href="https://www.researchgate.net/profile/Michael-Jordan-3/publication/303521286_Communication-efficient_distributed_statistical_learning/links/57d2689208ae5f03b48b61f8/Communication-efficient-distributed-statistical-learning.pdf">Michael Jordan and others' work about distributed statistical learning </a>, I started research on distributed learning. Jordan et al. replaced the global likelihood function by communication-efficient surrogate likelihood (CSL). However, they required that the loss functions are smooth and have at least second-order derivatives, which limits its application. For example, in studies about high expenses in insurance, researchers are interested in predicting quantiles with nonsmooth quantile loss functions. So <b>we investigated high-dimensional CQR estimation for distributed data</b>. 
  - title: My Interest 2
    image:
      src: /assets/img/work/p2.jpg
      alt: sand
    description: Our motivating example is the <a href="https://archive.ics.uci.edu/ml/datasets/Beijing+Multi-Site+Air-Quality+Data"> Beijing Air Quality data</a>. It contains hourly air pollutants data from 12 air-quality monitoring sites in Beijing from March 1, 2013 to February 28, 2017 and includes the 24 × 8 matrix-valued predictor, which is the daily observation (24 hourly measurements) of 8 variables. We have completed two works based on the dataset- <b>distributed matrix regression and online update matrix regression. Both models do not require communication/storage of original data but only some summary statistics are needed</b>.  
  - title: My Interest 3
    image:
      src: /assets/img/work/p3.jpg
      alt: sand
    description: Currently, I am focusing on decentralized learning. Based on Decentralized Gradient Descent (DGD), Wu et al. proposed <a href="https://arxiv.org/pdf/2205.08364.pdf">Network Gradient Desent (NGD)</a>, which can be statistically as efficient as the global estimator. I am working on <b>Byzantine-resilient decentralized learning based on NGD</b>, considering various robust aggregation rules and different types of attacks, such as fall of empires, hidden attack and max attack.
---

Here are my research experiences.
<br />
<br />
