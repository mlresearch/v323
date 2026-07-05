---
title: 'Disentangling Dynamical Systems: Causal Representation Learning Meets Local
  Sparse Attention'
booktitle: Proceedings of the Fifth Conference on Causal Learning and Reasoning
year: '2026'
volume: '323'
series: Proceedings of Machine Learning Research
month: 4
publisher: PMLR
abstract: Parametric system identification methods estimate the parameters of explicitly
  defined physical systems from data. Yet, they remain constrained by the need to
  provide an explicit function space, typically through a predefined library of candidate
  functions chosen via available domain knowledge. In contrast, deep learning can
  demonstrably model systems of broad complexity with high fidelity, but black-box
  function approximation typically fails to yield explicit descriptive or disentangled
  representations revealing the structure of a system. We develop a novel identifiability
  theorem, leveraging causal representation learning, to uncover disentangled representations
  of system parameters without structural assumptions. We derive a graphical criterion
  specifying when system parameters can be uniquely disentangled from raw trajectory
  data, up to permutation and diffeomorphism. Crucially, our analysis demonstrates
  that global causal structures provide a lower bound on the disentanglement guarantees
  achievable when considering local state-dependent causal structures. We instantiate
  system parameter identification as a variational inference problem, leveraging a
  sparsity-regularised transformer to uncover state-dependent causal structures. We
  empirically validate our approach across four synthetic domains, demonstrating its
  ability to recover highly disentangled representations that baselines fail to recover.
  Corroborating our theoretical analysis, our results confirm that enforcing local
  causal structure is often necessary for full identifiability.
layout: inproceedings
issn: 2640-3498
id: baumgartner26a
tex_title: 'Disentangling Dynamical Systems: Causal Representation Learning Meets
  Local Sparse Attention'
firstpage: 119
lastpage: 165
page: 119-165
order: 119
cycles: false
bibtex_editor: Mazaheri, Bijan and Hanson, Niels Richard
editor:
- given: Bijan
  family: Mazaheri
- given: Niels Richard
  family: Hanson
bibtex_author: Baumgartner, Markus W. and Lei, Anson and Watson, Joe and Posner, Ingmar
author:
- given: Markus W.
  family: Baumgartner
- given: Anson
  family: Lei
- given: Joe
  family: Watson
- given: Ingmar
  family: Posner
date: 2026-07-05
address:
container-title: Proceedings of the Fifth Conference on Causal Learning and Reasoning
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 7
  - 5
pdf: https://raw.githubusercontent.com/mlresearch/v323/main/assets/baumgartner26a/baumgartner26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
