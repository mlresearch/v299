---
title: Expansive Latent Planning for Sparse Reward Offline Reinforcement Learning
section: Oral
openreview: xQx1O7WXSA
abstract: Sampling-based motion planning algorithms excel at searching global solution
  paths in geometrically complex settings. However, classical approaches, such as
  RRT, are difficult to scale beyond low-dimensional search spaces and rely on privileged
  knowledge e.g. about collision detection and underlying state distances. In this
  work, we take a step towards the integration of sampling-based planning into the
  reinforcement learning framework to solve sparse-reward control tasks from high-dimensional
  inputs. Our method, called VELAP, determines sequences of waypoints through sampling-based
  exploration in a learned state embedding. Unlike other sampling-based techniques,
  we iteratively expand a tree-based memory of visited latent areas, which is leveraged
  to explore a larger portion of the latent space for a given number of search iterations.
  We demonstrate state-of-the-art results in learning control from offline data in
  the context of vision-based manipulation under sparse reward feedback. Our method
  extends the set of available planning tools in model-based reinforcement learning
  by adding a latent planner that searches globally for feasible paths instead of
  being bound to a fixed prediction horizon.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: gieselmann23a
month: 0
tex_title: Expansive Latent Planning for Sparse Reward Offline Reinforcement Learning
firstpage: 1
lastpage: 22
page: 1-22
order: 1
cycles: false
bibtex_author: Gieselmann, Robert and Pokorny, Florian T.
author:
- given: Robert
  family: Gieselmann
- given: Florian T.
  family: Pokorny
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
pdf: https://proceedings.mlr.press/v229/gieselmann23a/gieselmann23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
