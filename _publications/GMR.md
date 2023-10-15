--- 
title: "Gaussian Mixture Reduction with Composite Transportation Divergence" 
collection: publications 
date: 2023-10-10
venue: 'IEEE Transactions on Information Theory'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10275014' 
--- 

Qiong Zhang, **Archer Gong Zhang**, Jiahua Chen

Abstract: Gaussian mixtures are widely used for approximating density functions in various applications such as density estimation, belief propagation, and Bayesian filtering. These applications often utilize Gaussian mixtures as initial approximations that are updated recursively. A key challenge in these recursive processes stems from the exponential increase in the mixture’s order, resulting in intractable inference. To overcome the difficulty, the Gaussian mixture reduction (GMR), which approximates a high order Gaussian mixture by one with a lower order, can be used. Although existing clustering-based methods are known for their satisfactory performance and computational efficiency, their convergence properties and optimal targets remain unknown. In this paper, we propose a novel optimization-based GMR method based on composite transportation divergence (CTD). We develop a majorization-minimization algorithm for computing the reduced mixture and establish its theoretical convergence under general conditions. Furthermore, we demonstrate that many existing clustering-based methods are special cases of ours, effectively bridging the gap between optimization-based and clustering-based techniques. Our unified framework empowers users to select the most appropriate cost function in CTD to achieve superior performance in their specific applications. Through extensive empirical experiments, we demonstrate the efficiency and effectiveness of our proposed method, showcasing its potential in various domains.

[Available here](https://ieeexplore.ieee.org/abstract/document/10275014)
