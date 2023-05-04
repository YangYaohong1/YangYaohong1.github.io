---
layout: work
title: Research
slug: /research
items:
  - title: My Interest 1
    image:
      src: /assets/img/work/p1.jpg
      alt: water
    description: Inspired by <a href="https://www.researchgate.net/profile/Michael-Jordan-3/publication/303521286_Communication-efficient_distributed_statistical_learning/links/57d2689208ae5f03b48b61f8/Communication-efficient-distributed-statistical-learning.pdf">Michael Jordan and others' work about distributed statistical learning </a>, I started research on distributed learning. Jordan et al. replaced the global likelihood function by communication-efficient surrogate likelihood (CSL). However, they required that the loss functions are smooth and have at least second-order derivatives, which limits its scope of application. For example, in some studies about high expenses in insurance, researchers are interested in predicting quantiles with nonsmooth quantile loss functions. So <b>we investigated a communication-efficient high-dimensional CQR estimation for distributed data</b>. 
  - title: My Interest 2
    image:
      src: /assets/img/work/p2.jpg
      alt: sand
    description: Our motivating example is the <a href="https://archive.ics.uci.edu/ml/datasets/Beijing+Multi-Site+Air-Quality+Data"> Beijing Air Quality data</a>. It contains hourly air pollutants data from 12 nationally controlled air-quality monitoring sites in Beijing from March 1, 2013 to February 28, 2017 and includes the measurements as a 24 × 6 matrix-valued predictor, which is the daily observation (24 hourly measurements) of eight variables - SO3, NO2, CO, O3, TEMP (temperature), PRES (pressure), DEWP (dew point temperature) and WSPM (wind speed). The response is the daily aggregated count of PM2.5. There are two pieces of work that we did based on these characteristics - <b>distributed matrix regression and online update matrix regression. Both works do not require communicaiton/storage of original data but only some summary statistics are needed</b>.  
  - title: My Interest 3
    image:
      src: /assets/img/work/p3.jpg
      alt: sand
    description: Now, I am interested in federated learning with Byzantine attacks. Federated learning is highly related to distributed learning, where data are often distributed across a large number of clients (e.g. mobile devices). Based on Decentralized Gradient Descent (DGD), Wu et al. proposed <a href="https://arxiv.org/pdf/2205.08364.pdf">Network Gradient Desent (NGD)</a>, <b>however, how to extend NGD to the Byzantine attack scenario is under study</b>.
---

Here are my research experiences.
<br />
<br />
