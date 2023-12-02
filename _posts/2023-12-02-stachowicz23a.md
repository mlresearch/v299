---
title: 'FastRLAP: A System for Learning High-Speed Driving via Deep RL and Autonomous
  Practicing'
section: Poster
openreview: FRKBdXhkQE0
abstract: 'We present a system that enables an autonomous small-scale RC car to drive
  aggressively from visual observations using reinforcement learning (RL). Our system,
  FastRLAP, trains autonomously in the real world, without human interventions, and
  without requiring any simulation or expert demonstrations. Our system integrates
  a number of important components to make this possible: we initialize the representations
  for the RL policy and value function from a large prior dataset of other robots
  navigating in other environments (at low speed), which provides a navigation-relevant
  representation. From here, a sample-efficient online RL method uses a single low-speed
  user-provided demonstration to determine the desired driving course, extracts a
  set of navigational checkpoints, and autonomously practices driving through these
  checkpoints, resetting automatically on collision or failure. Perhaps surprisingly,
  we find that with appropriate initialization and choice of algorithm, our system
  can learn to drive over a variety of racing courses with less than 20 minutes of
  online training. The resulting policies exhibit emergent aggressive driving skills,
  such as timing braking and acceleration around turns and avoiding areas which impede
  the robot’s motion, approaching the performance of a human driver using a similar
  first-person interface over the course of training.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: stachowicz23a
month: 0
tex_title: 'FastRLAP: A System for Learning High-Speed Driving via Deep RL and Autonomous
  Practicing'
firstpage: 3100
lastpage: 3111
page: 3100-3111
order: 3100
cycles: false
bibtex_author: Stachowicz, Kyle and Shah, Dhruv and Bhorkar, Arjun and Kostrikov,
  Ilya and Levine, Sergey
author:
- given: Kyle
  family: Stachowicz
- given: Dhruv
  family: Shah
- given: Arjun
  family: Bhorkar
- given: Ilya
  family: Kostrikov
- given: Sergey
  family: Levine
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
pdf: https://proceedings.mlr.press/v229/stachowicz23a/stachowicz23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
