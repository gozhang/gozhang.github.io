--- 
title: "Resistant convex clustering: How does the fusion penalty enhance resistance?" 
collection: publications 
date: 2025-03-06
venue: 'Electronic Journal of Statistics'
paperurl: 'https://arxiv.org/abs/1906.09581' 
--- 

Qiang Sun, **Archer Gong Zhang**, Chenyu Liu, Kean Ming Tan

Abstract: Convex clustering is a convex relaxation of the k-means and hierarchical clustering. It involves solving a convex optimization problem with the objective function being a squared error loss plus a fusion penalty that encourages the estimated centroids for observations in the same cluster to be identical. However, when data are contaminated, convex clustering with a squared error loss fails even when there is only one arbitrary outlier. To address this challenge, we propose a resistant convex clustering method. Theoretically, we show that the new estimator is resistant to arbitrary outliers: it does not break down until more than half of the observations are arbitrary outliers. Perhaps surprisingly, the fusion penalty can help enhance resistance by fusing the estimators to the cluster centers of uncontaminated samples, but not the other way around. Numerical studies demonstrate the competitive performance of the proposed method. The R package is available at [Rcvxclustr](https://github.com/statsle/Rcvxclustr).

[Available here](https://projecteuclid.org/journals/electronic-journal-of-statistics/volume-19/issue-1/Resistant-convex-clustering--How-does-the-fusion-penalty-enhance/10.1214/25-EJS2359.full)
