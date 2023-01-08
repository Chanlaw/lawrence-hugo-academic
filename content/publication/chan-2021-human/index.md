---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Human irrationality: both bad and good for reward inference"
subtitle: ""
summary: "We study the effect of human irrationality on reward inference. We find that irrationality can both help and hurt reward inference, depending on the type of irrationality. We also find that the effect of irrationality on reward inference is not monotonic in the degree of irrationality."
authors:
  - admin
  - Andrew Critch
  - Anca Dragan
tags: []
categories: []
date: "2021-11-12"
lastmod: 2023-01-07T17:08:24-08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: "2023-01-08T01:08:24.327969Z"
publication_types:
  - "3"
abstract: ""
publication: "*arXiv preprint arXiv:2111.06956*"

abstract: "Assuming humans are (approximately) rational enables robots to infer reward functions by observing human behavior. But people exhibit a wide array of irrationalities, and our goal with this work is to better understand the effect they can have on reward inference. The challenge with studying this effect is that there are many types of irrationality, with varying degrees of mathematical formalization. We thus operationalize irrationality in the language of MDPs, by altering the Bellman optimality equation, and use this framework to study how these alterations would affect inference.
We find that wrongly modeling a systematically irrational human as noisy-rational performs a lot worse than correctly capturing these biases -- so much so that it can be better to skip inference altogether and stick to the prior! More importantly, we show that an irrational human, when correctly modelled, can communicate more information about the reward than a perfectly rational human can. That is, if a robot has the correct model of a human's irrationality, it can make an even stronger inference than it ever could if the human were rational. Irrationality fundamentally helps rather than hinder reward inference, but it needs to be correctly accounted for."

links:
  - name: arXiv
    url: https://arxiv.org/abs/2111.06956

url_pdf: "https://arxiv.org/pdf/2111.06956.pdf"
url_code: ""
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---
