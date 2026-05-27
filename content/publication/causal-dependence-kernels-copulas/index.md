---
title: "Detecting Changes in Causal Dependence with Kernels and Copulas"

authors:
- Shakeel Gavioli-Akilagun
- admin
- Francesco Quinzan

date: "2026-05-07T00:00:00Z"
# doi: ""

# Publication type.
# 3 = Preprint / Working Paper
publication_types: ["3"]

publication: arXiv preprint
# publication_short: arXiv

abstract: >
  We propose a framework for determining whether the causal dependence of an outcome Y on a covariate X changes at a given time point, given confounders Z. For instance, in financial markets, the effect of a market indicator on asset returns may causally change over time. While many existing measures of association can be used to detect changes in joint and marginal distributions, in the absence of strong assumptions on the data generating process none are suitable for detecting changes in the causal mechanism or in the strength of causal relationship. In this work we approach the problem from a fully non-parametric perspective, and treat the causal mechanism as well as the distribution of the data as unknown. We introduce a quantity based on the integrated difference between kernel mean embeddings of certain conditional copulas, which is provably equal to zero if the causal dependence does not change and strictly positive else. A near-linear time estimator for the quantity is proposed, with rates of convergence explicitly spelled out. Extensive experiments demonstrate that the proposed statistic achieves high accuracy on multiple synthetic and real-world datasets. We additionally show how the proposed statistic can be used for change point detection when the goal is to detect changes in causal dependence occurring at unknown times.

summary: >
  A non-parametric framework for detecting changes in causal dependence using kernel mean embeddings of conditional copulas, with near-linear estimation and change point detection applications.

tags: []

featured: true
weight: 210

links:
- name: PDF
  url: https://arxiv.org/pdf/2605.05809.pdf
- name: arXiv
  url: https://arxiv.org/abs/2605.05809

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  caption: 'Image credit: [**Pexels / Allen Boguslavsky**](https://www.pexels.com/photo/an-old-gas-pump-26840197/)'
  url: 'https://images.pexels.com/photos/26840197/pexels-photo-26840197.jpeg?auto=compress&cs=tinysrgb&w=1200'
  focal_point: ""
  preview_only: false
---
