---
layout: work
title: Research
slug: /research
items:
  - title: My Interest 1
    image:
      src: /assets/img/work/water.png
      alt: water
    description: Inspired by <a href="https://www.researchgate.net/profile/Michael-Jordan-3/publication/303521286_Communication-efficient_distributed_statistical_learning/links/57d2689208ae5f03b48b61f8/Communication-efficient-distributed-statistical-learning.pdf">Jordan et als work about distributed data </a>, I am interested in distributed learning. Jordan et al. replaced the global likelihood function by communication-efficient surrogate likelihood (CSL) and then proposed a general framework for distributed estimation that can be used in general smooth M-estimation, Bayesian estimation and high-dimensional penalized regression. They showed that the CSL could effectively reduce the transmission cost of the distributed data and reach the same convergence rate as the global likelihood-based estimation. However, this approach is hampered by the following two issues. First, to obtain some rigorous theoretical results, Jordan et al. (2019) required that the loss functions are smooth and have at least second-order derivatives, which limits its scope of application. For example, in some studies about the low weight in children growth, high expenses in insurance and so on, researchers are interested in predicting quantiles with nonsmooth quantile loss functions. Second, since distributed data are always collected from different sources with different locations and times, the homoscedasticity assumption is often not valid such that the ordinary M-estimator does not perform well when the error distribution is heavily skewed or data have outliers. So we investigated a communication-efficient sparse CQR estimation for distributed data with the Lasso penalty. An efficient ADMM algorithm is proposed to compute the estimator.

  - title: My Interest 2
    image:
      src: /assets/img/work/sand.png
      alt: sand
    description: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
---

This is an example of a "Work" page, displaying your work, your interests, your projects.
<br />
<br />
