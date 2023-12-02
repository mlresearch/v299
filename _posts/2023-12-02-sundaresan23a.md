---
title: 'KITE: Keypoint-Conditioned Policies for Semantic Manipulation'
section: Poster
openreview: veGdf4L4Xz
abstract: 'While natural language offers a convenient shared interface for humans
  and robots, enabling robots to interpret and follow language commands remains a
  longstanding challenge in manipulation. A crucial step to realizing a performant
  instruction-following robot is achieving semantic manipulation – where a robot interprets
  language at different specificities, from high-level instructions like "Pick up
  the stuffed animal" to more detailed inputs like "Grab the left ear of the elephant."
  To tackle this, we propose Keypoints + Instructions to Execution, a two-step framework
  for semantic manipulation which attends to both scene semantics (distinguishing
  between different objects in a visual scene) and object semantics (precisely localizing
  different parts within an object instance). KITE first grounds an input instruction
  in a visual scene through 2D image keypoints, providing a highly accurate object-centric
  bias for downstream action inference. Provided an RGB-D scene observation, KITE
  then executes a learned keypoint-conditioned skill to carry out the instruction.
  The combined precision of keypoints and parameterized skills enables fine-grained
  manipulation with generalization to scene and object variations. Empirically, we
  demonstrate KITE in 3 real-world environments: long-horizon 6-DoF tabletop manipulation,
  semantic grasping, and a high-precision coffee-making task. In these settings, KITE
  achieves a $75%$, $70%$, and $71%$ overall success rate for instruction-following,
  respectively. KITE outperforms frameworks that opt for pre-trained visual language
  models over keypoint-based grounding, or omit skills in favor of end-to-end visuomotor
  control, all while being trained from fewer or comparable amounts of demonstrations.
  Supplementary material, datasets, code, and videos can be found on our website:
  https://tinyurl.com/kite-site.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sundaresan23a
month: 0
tex_title: 'KITE: Keypoint-Conditioned Policies for Semantic Manipulation'
firstpage: 1006
lastpage: 1021
page: 1006-1021
order: 1006
cycles: false
bibtex_author: Sundaresan, Priya and Belkhale, Suneel and Sadigh, Dorsa and Bohg,
  Jeannette
author:
- given: Priya
  family: Sundaresan
- given: Suneel
  family: Belkhale
- given: Dorsa
  family: Sadigh
- given: Jeannette
  family: Bohg
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
pdf: https://proceedings.mlr.press/v229/sundaresan23a/sundaresan23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
