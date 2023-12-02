---
title: 'Heteroscedastic Gaussian Processes and Random Features: Scalable Motion Primitives
  with Guarantees'
section: Poster
openreview: GsM2qJTAg-
abstract: Heteroscedastic Gaussian processes (HGPs) are kernel-based, non-parametric
  models that can be used to infer nonlinear functions with time-varying noise. In
  robotics, they can be employed for learning from demonstration as motion primitives,
  i.e. as a model of the trajectories to be executed by the robot. HGPs provide variance
  estimates around the reference signal modeling the trajectory, capturing both the
  predictive uncertainty and the motion variability. However, similarly to standard
  Gaussian processes they suffer from a cubic complexity in the number of training
  points, due to the inversion of the kernel matrix. The uncertainty can be leveraged
  for more complex learning tasks, such as inferring the variable impedance profile
  required from a robotic manipulator. However, suitable approximations are needed
  to make HGPs scalable, at the price of potentially worsening the posterior mean
  and variance profiles. Motivated by these observations, we study the combination
  of HGPs and random features, which are a popular, data-independent approximation
  strategy of kernel functions. In a theoretical analysis, we provide novel guarantees
  on the approximation error of the HGP posterior due to random features. Moreover,
  we validate this scalable motion primitive on real robot data, related to the problem
  of variable impedance learning. In this way, we show that random features offer
  a viable and theoretically sound alternative for speeding up the trajectory processing,
  without sacrificing accuracy.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: caldarelli23a
month: 0
tex_title: 'Heteroscedastic Gaussian Processes and Random Features: Scalable Motion
  Primitives with Guarantees'
firstpage: 3010
lastpage: 3029
page: 3010-3029
order: 3010
cycles: false
bibtex_author: Caldarelli, Edoardo and Chatalic, Antoine and Colom\'{e}, Adri\`{a}
  and Rosasco, Lorenzo and Torras, Carme
author:
- given: Edoardo
  family: Caldarelli
- given: Antoine
  family: Chatalic
- given: Adrià
  family: Colomé
- given: Lorenzo
  family: Rosasco
- given: Carme
  family: Torras
date: 2023-12-02
address:
container-title: Proceedings of The 7th Conference on Robot Learning
volume: '229'
genre: inproceedings
issued:
  date-parts:
  - 2023
  - 12
  - 2
pdf: https://proceedings.mlr.press/v229/caldarelli23a/caldarelli23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
