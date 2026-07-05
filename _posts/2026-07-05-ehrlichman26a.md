---
title: Causal Discovery for Efficient Offline RL with Factored Action Spaces
booktitle: Proceedings of the Fifth Conference on Causal Learning and Reasoning
year: '2026'
volume: '323'
series: Proceedings of Machine Learning Research
month: 4
publisher: PMLR
abstract: Offline policy optimization is often sample-inefficient, especially when
  the action space is large, a problem that commonly arises in healthcare applications
  and multi-agent tasks. Many domains, however, admit a combinatorial action space,
  where sub-actions affect future states and rewards independently of one another.
  Past work either makes a priori assumptions about sub-action independence leading
  to efficient but potentially biased policy optimization, or fails to leverage potential
  independence, sacrificing sample efficiency. In contrast, we propose a two-step
  framework that leverages causal discovery for efficient policy optimization without
  introducing bias. Our approach (i) discovers the causal structure underlying the
  environment’s dynamics from observational data, and (ii) exploits this structure
  to restrict the admissible policy class to a simpler, unbiased class. We provide
  theoretical guarantees characterizing settings under which our approach leads to
  efficient unbiased policy learning. Empirically, we demonstrate that our approach
  leads to more efficient policy optimization in settings with limited observational
  data, across both single-agent healthcare tasks and multi-agent settings. Our code
  is available at https://github.com/cehr123/DiFaRL.
layout: inproceedings
issn: 2640-3498
id: ehrlichman26a
tex_title: Causal Discovery for Efficient Offline RL with Factored Action Spaces
firstpage: 1424
lastpage: 1449
page: 1424-1449
order: 1424
cycles: false
bibtex_editor: Mazaheri, Bijan and Hanson, Niels Richard
editor:
- given: Bijan
  family: Mazaheri
- given: Niels Richard
  family: Hanson
bibtex_author: Ehrlichman, Cecilia and Dykstra, Michael and Tang, Shengpu and Makar,
  Maggie
author:
- given: Cecilia
  family: Ehrlichman
- given: Michael
  family: Dykstra
- given: Shengpu
  family: Tang
- given: Maggie
  family: Makar
date: 2026-07-05
address:
container-title: Proceedings of the Fifth Conference on Causal Learning and Reasoning
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 7
  - 5
pdf: https://raw.githubusercontent.com/mlresearch/v323/main/assets/ehrlichman26a/ehrlichman26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
