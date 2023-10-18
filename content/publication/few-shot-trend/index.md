---
title: "Few-Shot Learning Patterns in Financial Time-Series for Trend-Following Strategies"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Samuel Kessler
- Stephen J. Roberts
- Stefan Zohren

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2023-10-17T00:00:00Z"
# doi: "10.3905/jfds.2021.1.081"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In the Journal of Financial Data Science
# publication_short: In *ICW*

abstract: Forecasting models for systematic trading strategies do not adapt quickly when financial market conditions change, as was seen in the advent of the COVID-19 pandemic in 2020, when market conditions changed dramatically causing many forecasting models to take loss-making positions. To deal with such situations, we propose a novel time-series trend-following forecaster that is able to quickly adapt to new market conditions, referred to as regimes. We leverage recent developments from the deep learning community and use few-shot learning. We propose the Cross Attentive Time-Series Trend Network - X-Trend - which takes positions attending over a context set of financial time-series regimes. X-Trend transfers trends from similar patterns in the context set to make predictions and take positions for a new distinct target regime. X-Trend is able to quickly adapt to new financial regimes with a Sharpe ratio increase of 18.9% over a neural forecaster and 10-fold over a conventional Time-series Momentum strategy during the turbulent market period from 2018 to 2023. Our strategy recovers twice as quickly from the COVID-19 drawdown compared to the neural-forecaster. X-Trend can also take zero-shot positions on novel unseen financial assets obtaining a 5-fold Sharpe ratio increase versus a neural time-series trend forecaster over the same period. X-Trend both forecasts next-day prices and outputs a trading signal. Furthermore, the cross-attention mechanism allows us to interpret the relationship between forecasts and patterns in the context set.

# Summary. An optional shortened abstract.
summary: We propose a novel time-series trend-following forecaster that is able to quickly adapt to new market conditions, referred to as regimes. We leverage recent developments from the deep learning community and use few-shot learning. We propose the Cross Attentive Time-Series Trend Network - X-Trend - which takes positions attending over a context set of financial time-series regimes. X-Trend transfers trends from similar patterns in the context set to make predictions and take positions for a new distinct target regime. X-Trend can also take zero-shot positions on novel unseen financial assets. It both forecasts next-day prices and outputs a trading signal. Furthermore, the cross-attention mechanism allows us to interpret the relationship between forecasts and patterns in the context set.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: PDF
  url: https://arxiv.org/pdf/2310.10500.pdf

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Pexels**](https://www.pexels.com/photo/magnifying-glass-on-top-of-document-6801648/)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
