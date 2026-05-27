---
title: "DeRegiME: Deep Regime Mixtures for Probabilistic Forecasting under Distribution Shift"

authors:
- admin
- Stefan Zohren
- Stephen J. Roberts

date: "2026-05-19T00:00:00Z"
# doi: ""

# Publication type.
# 3 = Preprint / Working Paper
publication_types: ["3"]

publication: arXiv preprint
# publication_short: arXiv

abstract: >
  We introduce DeRegiME -- Deep Regime Mixture of Experts -- a direct multi-horizon probabilistic forecaster that separates latent uncertainty regimes from the underlying signal and softly assigns each forecast location to learned recurring regimes using a sparse variational Gaussian process (GP) whose nonstationary regime-mixing kernel and Student-t likelihood combine per-regime sub-kernels and noise processes via a shared gate. This yields a single sparse-GP posterior, not a mixture of GP experts. DeRegiME addresses a key limitation of neural forecasters: point forecasts discard residual uncertainty, and probabilistic heads -- whether single marginals, uninterpreted mixtures, quantile sets, or diffusion samples -- rarely expose the regime structure of the residual. Yet distribution shift in noisy heteroskedastic time series may be abrupt, gradual, or horizon-dependent and often appears in residual uncertainty rather than the conditional mean. DeRegiME yields an interpretable mean-residual-noise decomposition with a direct-sum feature-space representation that anchors regimes as clusters of residual similarity whose transitions surface as implicit changepoints. The effective number of regimes is pruned by the stick-breaking gate. We prove kernel validity and predictive-density propriety, and across ten benchmarks and three encoder grids DeRegiME improves negative log predictive density (NLPD) by 20.3% over the strongest encoder-matched baseline, a DeepAR/GluonTS-style dynamic Student-t head, with parallel gains on CRPS (3.0%) and MSE (4.7%). Improvements are consistent across all datasets, which span abrupt, gradual, and seasonal shifts.

summary: >
  A direct multi-horizon probabilistic forecaster that separates latent uncertainty regimes from the underlying signal, exposing regime shifts in residual uncertainty with a sparse variational GP.

tags: []

featured: true
weight: 220

links:
- name: PDF
  url: https://arxiv.org/pdf/2605.19231.pdf
- name: arXiv
  url: https://arxiv.org/abs/2605.19231

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  caption: 'Image credit: [**Pexels / Jerson Vargas**](https://www.pexels.com/photo/close-up-of-sound-waves-on-a-computer-screen-4765390/)'
  url: 'https://images.pexels.com/photos/4765390/pexels-photo-4765390.jpeg?auto=compress&cs=tinysrgb&w=1200'
  focal_point: ""
  preview_only: false
---
