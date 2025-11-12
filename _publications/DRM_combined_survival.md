--- 
title: "Density ratio model for multiple types of survival data with empirical likelihood" 
collection: publications 
date: 2025-11-12
venue: 'Submitted'
--- 

James Hugh McVittie, **Archer Gong Zhang**

(The two authors make equal contributions.)

Abstract: The density ratio model (DRM) is a semiparametric model that relates the distributions from multiple samples to a nonparametrically defined reference distribution via exponential tilting, with finite-dimensional parameters governing their differences in shape. When multiple types of partially observed (censored/truncated) failure time data are collected in an observational study, the DRM can be utilized to conduct a single unified analysis of the combined data. 
In this paper, we extend the methodology for censored length-biased/truncated data to the DRM framework and formulate the inference using empirical likelihood. 
We develop an EM algorithm to compute the DRM-based maximum empirical likelihood estimators of the model parameters and survival function, and assess its performance through extensive simulations under correct model specification, overspecification, and misspecification, across a range of failure-time distributions and censoring proportions.
We also illustrate the efficacy of our method by analyzing the duration of time spent from admission to discharge in a Montreal-area hospital in Canada.
The R code that implements our method is available on GitHub at [DRM-combined-survival](https://github.com/gozhang/DRM-combined-survival).

R code [`DRM-combined-survival`](https://github.com/gozhang/DRM-combined-survival)
