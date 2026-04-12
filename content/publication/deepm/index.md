---
title: "DeePM: Regime-Robust Deep Learning for Systematic Macro Portfolio Management"

authors:
- admin
- Stephen J. Roberts
- Stefan Zohren

date: "2026-01-10T00:00:00Z"
# doi: ""

# Publication type.
# 3 = Preprint / Working Paper
publication_types: ["3"]

publication: arXiv preprint
# publication_short: arXiv

abstract: >
  We propose DeePM (Deep Portfolio Manager), a structured deep-learning macro portfolio manager trained end-to-end to maximize a robust, risk-adjusted utility. DeePM addresses three fundamental challenges in financial learning: (1) it resolves the asynchronous "ragged filtration" problem via a Directed Delay (Causal Sieve) mechanism that prioritizes causal impulse-response learning over information freshness; (2) it combats low signal-to-noise ratios via a Macroeconomic Graph Prior, regularizing cross-asset dependence according to economic first principles; and (3) it optimizes a distributionally robust objective where a smooth worst-window penalty serves as a differentiable proxy for Entropic Value-at-Risk (EVaR) - a window-robust utility encouraging strong performance in the most adverse historical subperiods. In large-scale backtests from 2010-2025 on 50 diversified futures with highly realistic transaction costs, DeePM attains net risk-adjusted returns that are roughly twice those of classical trend-following strategies and passive benchmarks, solely using daily closing prices. Furthermore, DeePM improves upon the state-of-the-art Momentum Transformer architecture by roughly fifty percent. The model demonstrates structural resilience across the 2010s "CTA (Commodity Trading Advisor) Winter" and the post-2020 volatility regime shift, maintaining consistent performance through the pandemic, inflation shocks, and the subsequent higher-for-longer environment. Ablation studies confirm that strictly lagged cross-sectional attention, graph prior, principled treatment of transaction costs, and robust minimax optimization are the primary drivers of this generalization capability

summary: >
  We propose DeePM (Deep Portfolio Manager), a structured deep-learning macro portfolio manager trained end-to-end to maximize a robust, risk-adjusted utility. DeePM addresses three fundamental challenges in financial learning: (1) it resolves the asynchronous "ragged filtration" problem via a Directed Delay (Causal Sieve) mechanism that prioritizes causal impulse-response learning over information freshness; (2) it combats low signal-to-noise ratios via a Macroeconomic Graph Prior, regularizing cross-asset dependence according to economic first principles; and (3) it optimizes a distributionally robust objective where a smooth worst-window penalty serves as a differentiable proxy for Entropic Value-at-Risk (EVaR) - a window-robust utility encouraging strong performance in the most adverse historical subperiods.

tags: []

featured: true
weight: 200

links:
- name: PDF
  url: https://arxiv.org/pdf/2601.05975.pdf
- name: arXiv
  url: https://arxiv.org/abs/2601.05975
- name: Code
  url: https://github.com/kieranjwood/deepm

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  caption: 'Image credit: [**Pexels**]("https://images.pexels.com/photos/8566468/)'
  focal_point: ""
  preview_only: false
---
