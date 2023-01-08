---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Causal Scrubbing: a method for rigorously testing interpretability hypotheses"
subtitle: ""
summary: "We introduce a more principled approach for evaluating the quality of mechanistic interpretations via _behavior-preserving resampling ablations_---converting hypotheses into classes of activations inside a neural network can be resampled without affecting behavior."
authors:
  - admin
  - Adrià Garriga-Alonso
  - Nicholas Goldowsky-Dill
  - Ryan Greenblatt
  - Jenny Nitishinskaya
  - Ansh Radhakrishnan
  - Buck Shlegeris
  - Nate Thomas
author_notes:
  -
  -
  -
  -
  -
  -
  -
  - "Authors ordered alphabetically by last name"

tags: [Mechanistic Interpretability]
categories: []
date: "2022-12-02"
lastmod: 2023-01-07T17:08:27-08:00
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
publishDate: "2023-01-08T01:08:26.857406Z"
publication_types:
  - "0"
abstract: ""
publication: AI Alignment Forum

abstract: "We introduce causal scrubbing, a principled approach for evaluating the quality of mechanistic interpretations. The key insight behind this work is that mechanistic interpretability hypotheses can be thought of as defining what activations inside a neural network can be resampled without affecting behavior. Accordingly, causal scrubbing tests interpretability hypotheses via behavior-preserving resampling ablations---converting hypotheses into distributions over activations that should preserve behavior, and checking if behavior is actually preserved.

 We apply this method to develop a refined understanding of how a small language model implements induction and how an algorithmic model correctly classifies if a sequence of parentheses is balanced."

links:
  - name: Alignment Forum
    url: https://www.alignmentforum.org/posts/JvZhhzycHu2Yd57RN/causal-scrubbing-a-method-for-rigorously-testing

url_pdf:
url_code:
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---
