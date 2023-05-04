---
layout: work
title: Research
slug: /research
items:
  - title: My Interest 1
    image:
      src: /assets/img/work/water.png
      alt: water
    description: Inspired by <a href="https://www.researchgate.net/profile/Michael-Jordan-3/publication/303521286_Communication-efficient_distributed_statistical_learning/links/57d2689208ae5f03b48b61f8/Communication-efficient-distributed-statistical-learning.pdf">Michael Jordan and others' work about distributed statistical learning </a>, I started research on distributed learning. Jordan et al. replaced the global likelihood function by communication-efficient surrogate likelihood (CSL). However, this approach is hampered by the following two issues. First, to obtain some rigorous theoretical results, Jordan et al. required that the loss functions are smooth and have at least second-order derivatives, which limits its scope of application. For example, in some studies about the low weight in children growth, high expenses in insurance and so on, researchers are interested in predicting quantiles with nonsmooth quantile loss functions. Second, since distributed data are always collected from different sources with different locations and times, the homoscedasticity assumption is often not valid such that the ordinary M-estimator does not perform well when the error distribution is heavily skewed or data have outliers. So we investigated a communication-efficient sparse CQR estimation for distributed data with the Lasso penalty. 
  - title: My Interest 2
    image:
      src: /assets/img/work/sand.png
      alt: sand
    description: Furtermore, I considerd the matrix regression and two pieces of work about distributed quantile matrix regression and online matrix gression are conducted. 
     
  - title: My Interest 3
    image:
      src: /assets/img/work/sand.png
      alt: sand
    description: Now, I am interested in federated learning with Byzantine attacks. Based on Decentralized Gradient Descent (DGD), Wu et al. proposed Network Gradient Desent (NGD), however, how can NGD be extended to situations with Byzantine attacks is under inverstigation.
---

Here are my research experience.
<br />
<br />
