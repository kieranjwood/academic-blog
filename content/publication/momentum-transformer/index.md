---
title: "Trading with the Momentum Transformer: An Intelligent and Interpretable Architecture"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Sven Giegerich
- Stephen Roberts
- Stefan Zohren

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-12-17T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
# publication: In *Wowchemy Conference*
# publication_short: In *ICW*

abstract: Deep learning architectures, specifically Deep Momentum Networks (DMNs) [1904.04912], have been found to be an effective approach to momentum and mean-reversion trading. However, some of the key challenges in recent years involve learning long-term dependencies, degradation of performance when considering returns net of transaction costs and adapting to new market regimes, notably during the SARS-CoV-2 crisis. Attention mechanisms, or Transformer-based architectures, are a solution to such challenges because they allow the network to focus on significant time steps in the past and longer-term patterns. We introduce the Momentum Transformer, an attention-based architecture which outperforms the benchmarks, and is inherently interpretable, providing us with greater insights into our deep learning trading strategy. Our model is an extension to the LSTM-based DMN, which directly outputs position sizing by optimising the network on a risk-adjusted performance metric, such as Sharpe ratio. We find an attention-LSTM hybrid Decoder-Only Temporal Fusion Transformer (TFT) style architecture is the best performing model. In terms of interpretability, we observe remarkable structure in the attention patterns, with significant peaks of importance at momentum turning points. The time series is thus segmented into regimes and the model tends to focus on previous time-steps in alike regimes. We find changepoint detection (CPD) [2105.13727], another technique for responding to regime change, can complement multi-headed attention, especially when we run CPD at multiple timescales. Through the addition of an interpretable variable selection network, we observe how CPD helps our model to move away from trading predominantly on daily returns data. We note that the model can intelligently switch between, and blend, classical strategies - basing its decision on patterns in the data.

# Summary. An optional shortened abstract.
summary: Deep learning architectures, specifically Deep Momentum Networks (DMNs), have been found to be an effective approach to momentum and mean-reversion trading. However, some of the key challenges in recent years involve learning long-term dependencies, degradation of performance when considering returns net of transaction costs and adapting to new market regimes, notably during the SARS-CoV-2 crisis. Attention mechanisms, or Transformer-based architectures, are a solution to such challenges because they allow the network to focus on significant time steps in the past and longer-term patterns. We introduce the Momentum Transformer, an attention-based architecture which outperforms the benchmarks, and is inherently interpretable, providing us with greater insights into our deep learning trading strategy. Our model is an extension to the LSTM-based DMN, which directly outputs position sizing by optimising the network on a risk-adjusted performance metric, such as Sharpe ratio. We observe remarkable structure in the attention patterns, with significant peaks of importance at momentum turning points. The time series is thus segmented into regimes and the model tends to focus on previous time-steps in alike regimes. Through the addition of an interpretable variable selection network, we observe how CPD helps our model to move away from trading predominantly on daily returns data. We note that the model can intelligently switch between, and blend, classical strategies - basing its decision on patterns in the data.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: PDF
  url: https://arxiv.org/pdf/2112.08534.pdf

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
