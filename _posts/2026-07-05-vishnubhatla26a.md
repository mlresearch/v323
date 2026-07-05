---
title: Proxy-Guided Measurement Calibration
booktitle: Proceedings of the Fifth Conference on Causal Learning and Reasoning
year: '2026'
volume: '323'
series: Proceedings of Machine Learning Research
month: 4
publisher: PMLR
abstract: Aggregate outcome variables collected through surveys and administrative
  records are often subject to systematic measurement error. For instance, in disaster
  loss databases, county-level losses reported may differ from the true damages due
  to variations in on-the-ground data collection capacity, reporting practices, and
  event characteristics. Such miscalibration complicates downstream analysis and decision-making.
  We study the problem of outcome miscalibration and propose a framework guided by
  proxy variables for estimating and correcting the systematic errors. We model the
  data-generating process using a causal graph that separates latent content variables
  driving the true outcome from the latent bias variables that induce systematic errors.
  The key insight is that proxy variables that depend on the true outcome but are
  independent of the bias mechanism provide identifying information for quantifying
  the bias. Leveraging this structure, we introduce a two-stage approach that utilizes
  variational autoencoders to disentangle content and bias latents, enabling us to
  estimate the effect of bias on the outcome of interest. We analyze the assumptions
  underlying our approach and evaluate it on synthetic data, semi-synthetic datasets
  derived from randomized trials, and a real-world case study of disaster loss reporting.
  Our code will be publicly available.
layout: inproceedings
issn: 2640-3498
id: vishnubhatla26a
tex_title: Proxy-Guided Measurement Calibration
firstpage: 1604
lastpage: 1634
page: 1604-1634
order: 1604
cycles: false
bibtex_editor: Mazaheri, Bijan and Hanson, Niels Richard
editor:
- given: Bijan
  family: Mazaheri
- given: Niels Richard
  family: Hanson
bibtex_author: Vishnubhatla, Saketh and Wan, Shu and Harrison, Andre and Raglin, Adrienne
  and Liu, Huan
author:
- given: Saketh
  family: Vishnubhatla
- given: Shu
  family: Wan
- given: Andre
  family: Harrison
- given: Adrienne
  family: Raglin
- given: Huan
  family: Liu
date: 2026-07-05
address:
container-title: Proceedings of the Fifth Conference on Causal Learning and Reasoning
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 7
  - 5
pdf: https://raw.githubusercontent.com/mlresearch/v323/main/assets/vishnubhatla26a/vishnubhatla26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
