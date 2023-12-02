---
title: Enabling Efficient, Reliable Real-World Reinforcement Learning with Approximate
  Physics-Based Models
section: Poster
openreview: TWgoGdubPN
abstract: We focus on developing efficient and reliable policy optimization strategies
  for robot learning with real-world data.  In recent years, policy gradient methods
  have emerged as a promising paradigm for training control policies in simulation.  However,
  these approaches often remain too data inefficient or unreliable to train on real
  robotic hardware. In this paper we introduce a novel policy gradient-based policy
  optimization framework which systematically leverages a (possibly highly simplified)
  first-principles model and enables learning precise control policies with limited
  amounts of real-world data. Our approach $1)$ uses the derivatives of the model
  to produce sample-efficient estimates of the policy gradient and $2)$ uses the model
  to design a low-level tracking controller, which is embedded in the policy class.
  Theoretical analysis provides insight into how the presence of this feedback controller
  addresses overcomes key limitations of stand-alone policy gradient methods, while
  hardware experiments with a small car and quadruped demonstrate that our approach
  can learn precise control strategies reliably and with only minutes of real-world
  data.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: westenbroek23a
month: 0
tex_title: Enabling Efficient, Reliable Real-World Reinforcement Learning with Approximate
  Physics-Based Models
firstpage: 2478
lastpage: 2497
page: 2478-2497
order: 2478
cycles: false
bibtex_author: Westenbroek, Tyler and Levy, Jacob and Fridovich-Keil, David
author:
- given: Tyler
  family: Westenbroek
- given: Jacob
  family: Levy
- given: David
  family: Fridovich-Keil
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
pdf: https://proceedings.mlr.press/v229/westenbroek23a/westenbroek23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
