---
title: Robot Learning with Sensorimotor Pre-training
section: Oral
openreview: 3gh9hf3R6x
abstract: We present a self-supervised sensorimotor pre-training approach for robotics.
  Our model, called RPT, is a Transformer that operates on sequences of sensorimotor
  tokens. Given a sequence of camera images, proprioceptive robot states, and actions,
  we encode the sequence into tokens, mask out a subset, and train a model to predict
  the missing content from the rest. We hypothesize that if a robot can predict the
  masked-out content it will have acquired a good model of the physical world that
  can enable it to act. RPT is designed to operate on latent visual representations
  which makes prediction tractable, enables scaling to larger models, and allows fast
  inference on a real robot. To evaluate our approach, we collected a dataset of 20,000
  real-world trajectories over 9 months using a combination of motion planning and
  grasping algorithms. We find that sensorimotor pre-training consistently outperforms
  training from scratch, has favorable scaling properties, and enables transfer across
  different tasks, environments, and robots.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: radosavovic23a
month: 0
tex_title: Robot Learning with Sensorimotor Pre-training
firstpage: 683
lastpage: 693
page: 683-693
order: 683
cycles: false
bibtex_author: Radosavovic, Ilija and Shi, Baifeng and Fu, Letian and Goldberg, Ken
  and Darrell, Trevor and Malik, Jitendra
author:
- given: Ilija
  family: Radosavovic
- given: Baifeng
  family: Shi
- given: Letian
  family: Fu
- given: Ken
  family: Goldberg
- given: Trevor
  family: Darrell
- given: Jitendra
  family: Malik
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
pdf: https://proceedings.mlr.press/v229/radosavovic23a/radosavovic23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
