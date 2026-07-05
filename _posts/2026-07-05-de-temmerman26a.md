---
title: Composite Graphical Causal Models for Inference on Heterogeneous-Indexed Data
booktitle: Proceedings of the Fifth Conference on Causal Learning and Reasoning
year: '2026'
volume: '323'
series: Proceedings of Machine Learning Research
month: 4
publisher: PMLR
abstract: Complex real-world systems typically consist of multiple interdependent
  subsystems, where each subsystem can operate under different sampling references.
  Consequently, the data collected across these subsystems vary in indexing (e.g.,
  time-, distance-, event-indexed), sampling frequency, or faces index misalignment.
  To approximately model such kind of systems, surrogate models can be used to serve
  as a computationally-inexpensive replacement during optimization, sensitivity analysis,
  uncertainty quantification, or interpretation. Conventional modeling approaches
  require these datasets to be unified into a single, uniformly-indexed table via
  preprocessing steps such as aggregation and merging. In this work, we introduce
  a novel approach, Composite Graphical Causal Models (CGCMs), that preserves the
  original indexing of each data table during both training and inference. By embedding
  resampling and aggregation operations directly within a GCM, our method eliminates
  the need for data homogenization as a preprocessing step. Specifically, a set of
  GCMs is employed each tailored to a distinct indexing, and connected using aggregation
  functions to model cross-index dependencies. As validated on synthetic datasets,
  this design enables a more representative modeling of heterogeneous-indexed processes,
  improving predictive performance and interpretability.
layout: inproceedings
issn: 2640-3498
id: de-temmerman26a
tex_title: Composite Graphical Causal Models for Inference on Heterogeneous-Indexed
  Data
firstpage: 887
lastpage: 910
page: 887-910
order: 887
cycles: false
bibtex_editor: Mazaheri, Bijan and Hanson, Niels Richard
editor:
- given: Bijan
  family: Mazaheri
- given: Niels Richard
  family: Hanson
bibtex_author: De Temmerman, Arne and Verbeke, Mathias
author:
- given: Arne
  family: De Temmerman
- given: Mathias
  family: Verbeke
date: 2026-07-05
address:
container-title: Proceedings of the Fifth Conference on Causal Learning and Reasoning
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 7
  - 5
pdf: https://raw.githubusercontent.com/mlresearch/v323/main/assets/de-temmerman26a/de-temmerman26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
