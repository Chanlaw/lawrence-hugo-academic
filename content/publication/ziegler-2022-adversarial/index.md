---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Adversarial Training for High-Stakes Reliability
subtitle: ""
summary: "We study the limits of adversarial training on a injury classification task using a variety of attacks including a new saliency map--based snippet rewrite tool to assist our human adversaries. While advesarial training was not able to eliminate all in-distribution failures, it did increase robustness to the adversarial attacks that we trained on."
authors:
  - Daniel M Ziegler
  - Seraphina Nix
  - admin
  - Tim Bauman
  - Peter Schmidt-Nielsen
  - Tao Lin
  - Adam Scherlis
  - Noa Nabeshima
  - Ben Weinstein-Raun
  - Daniel de Haas
  - " others"
tags: []
categories: []
date: "2022-05-03"
lastmod: 2023-01-07T17:08:26-08:00
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
publishDate: "2023-01-08T01:08:26.359029Z"
publication_types:
  - "1"
abstract: "In the future, powerful AI systems may be deployed in high-stakes settings, where a single failure could be catastrophic. One technique for improving AI safety in high-stakes settings is adversarial training, which uses an adversary to generate examples to train on in order to achieve better worst-case performance.
In this work, we used a safe language generation task (``avoid injuries'') as a testbed for achieving high reliability through adversarial training. We created a series of adversarial training techniques -- including a tool that assists human adversaries -- to find and eliminate failures in a classifier that filters text completions suggested by a generator. In our task, we determined that we can set very conservative classifier thresholds without significantly impacting the quality of the filtered outputs. We found that adversarial training increased robustness to the adversarial attacks that we trained on -- doubling the time for our contractors to find adversarial examples both with our tool (from 13 to 26 minutes) and without (from 20 to 44 minutes) -- without affecting in-distribution performance.
We hope to see further work in the high-stakes reliability setting, including more powerful tools for enhancing human adversaries and better ways to measure high levels of reliability, until we can confidently rule out the possibility of catastrophic deployment-time failures of powerful models."
publication: "*NeurIPS 2022*"


links:
  - name: ArXiv Preprint
    url: "https://arxiv.org/abs/2205.01663"

url_pdf: "https://arxiv.org/pdf/2205.01663.pdf"
url_code:
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---
