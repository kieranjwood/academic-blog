---
title: "Macro-aware time series forecasting via hierarchical mixed-frequency attention models"

authors:
- Daniel Cunha Oliveira
- admin
- Stefan Zohren
- Mihai Cucuringu
- André Fujita

date: "2026-05-30T00:00:00Z"
doi: "10.48550/arXiv.2606.00624"

# Publication type.
# 3 = Preprint / Working Paper
publication_types: ["3"]

publication: arXiv preprint
# publication_short: arXiv

abstract: >
  Deep learning models show promise in financial forecasting, yet their generalization is often undermined by small datasets, noisy signals, and non-stationarity. While meta-learning and related techniques mitigate some of these issues, they typically do not account for a core limitation in macro-financial prediction: the scarcity of distinct macroeconomic regimes that drive asset returns. We introduce HANET (Hierarchical Attention Network), a hybrid LSTM-based architecture that integrates macroeconomic domain knowledge through attention over long-run macro contexts while preserving high-frequency market dynamics. HANET organizes information in a hierarchical mixed-frequency structure, with daily asset-return signals nested within monthly macroeconomic windows, and introduces a Hierarchical Cross-Attention mechanism that reconciles low-frequency macro signals with high-frequency returns without discarding granular daily information. By framing regime selection as attention over macroeconomic contexts, the model adapts to scarce and shifting regimes. Empirically, across 55 liquid futures spanning multiple asset classes, HANET consistently outperforms neural forecasters that ignore macroeconomic information, particularly during turbulent periods, improving risk-adjusted returns and mitigating losses. Ablation studies show that these gains rely on structured macro conditioning rather than naive feature augmentation: an LSTM with the same macro representation performs poorly, and shuffling macro contexts substantially degrades performance. Finally, HANET provides interpretability through attention weights, highlighting which historical regimes are most influential for each forecast and linking macro conditions to portfolio outcomes. These results establish HANET as a systematic approach to integrating macroeconomic information into attention-based deep learning for financial forecasting.

summary: >
  Introduces HANET, a hierarchical attention network that nests daily asset-return signals within monthly macroeconomic contexts, using cross-attention to adapt to scarce and shifting macro regimes while preserving higher-frequency market dynamics.

tags: []

featured: true
weight: 215

links:
- name: PDF
  url: https://arxiv.org/pdf/2606.00624.pdf
- name: arXiv
  url: https://arxiv.org/abs/2606.00624

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  caption: 'Image credit: [**Unsplash / Kphotography**](https://unsplash.com/photos/a-display-in-a-grocery-store-filled-with-lots-of-vegetables-N4dq4Q0XLI8)'
  url: 'https://images.unsplash.com/photo-1705736624388-4f8390d9a9a7?auto=format&fit=crop&w=1200&q=80'
  focal_point: ""
  preview_only: false
---
