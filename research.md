---
layout: work
title: Research
slug: /research
items:
  - title: My Interest 1
    image:
      src: /assets/img/work/water.png
      alt: water
    description: Inspired by <a href="https://www.researchgate.net/profile/Michael-Jordan-3/publication/303521286_Communication-efficient_distributed_statistical_learning/links/57d2689208ae5f03b48b61f8/Communication-efficient-distributed-statistical-learning.pdf">Michael Jordan and others' work about distributed statistical learning </a>, I started research on distributed learning. Jordan et al. replaced the global likelihood function by communication-efficient surrogate likelihood (CSL). However, they required that the loss functions are smooth and have at least second-order derivatives, which limits its scope of application. For example, in some studies about high expenses in insurance, researchers are interested in predicting quantiles with nonsmooth quantile loss functions. So we investigated a communication-efficient high-dimensional CQR estimation for distributed data. 
  - title: My Interest 2
    image:
      src: /assets/img/work/sand.png
      alt: sand
    description: Our motivating example is the <a href="https://archive.ics.uci.edu/ml/datasets/Beijing+Multi-Site+Air-Quality+Data"> Beijing Air Quality data</a>. It contains hourly air pollutants data from 12 nationally controlled air-quality monitoring sites in Beijing from March 1, 2013 to February 28, 2017 and includes the measurements as a 24 × 6 matrix-valued predictor, which is the daily observation (24 hourly measurements) of eight variables- SO3, NO2, CO, O3, TEMP (temperature), PRES (pressure), DEWP (dew point temperature) and WSPM (wind speed). The response is the daily aggregated count of PM2.5. There are two pieces of work that we did based on these characteristics-distributed matrix regression and online update matrix regression. Both works do not require communicaiton/storage of original data but only some summary statistics.  
  - title: My Interest 3
    image:
      src: /assets/img/work/sand.png
      alt: sand
    description: Now, I am interested in federated learning with Byzantine attacks. Based on Decentralized Gradient Descent (DGD), Wu et al. proposed Network Gradient Desent (NGD), however, how can NGD be extended to situations with Byzantine attacks is under inverstigation.
---

Here are my research experience.
<br />
<br />
