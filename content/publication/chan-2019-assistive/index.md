---
# Documentation: https://wowchemy.com/docs/managing-content/

title: The assistive multi-armed bandit
subtitle: ""
summary: We study the problem of learning to assist a human who is *themselves learning* about their preferences.
authors:
  - admin
  - Dylan Hadfield-Menell
  - Siddhartha Srinivasa
  - Anca Dragan
tags: []
categories: []
date: "2019-03-11"
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
publishDate: "2023-01-08T01:08:24.073598Z"
# 0 = Uncategorized 1 = Conference paper 2 = Journal article 3 = Preprint / Working Paper 4 = Report 5 = Book 6 = Book section 7 = Thesis 8 = Patent
publication_types:
  - "1"
abstract: ""
publication:
  "*2019 14th ACM/IEEE International Conference on Human-Robot Interaction
  (HRI)*"
publication_short: HRI 2019

abstract: "Learning preferences implicit in the choices humans make is a well studied problem in both economics and computer science. However, most work makes the assumption that humans are acting (noisily) optimally with respect to their preferences. Such approaches can fail when people are themselves learning about what they want. In this work, we introduce the assistive multi-armed bandit, where a robot assists a human playing a bandit task to maximize cumulative reward. In this problem, the human does not know the reward function but can learn it through the rewards received from arm pulls; the robot only observes which arms the human pulls but not the reward associated with each pull. We offer sufficient and necessary conditions for successfully assisting the human in this framework. Surprisingly, better human performance in isolation does not necessarily lead to better performance when assisted by the robot: a human policy can do better by effectively communicating its observed rewards to the robot. We conduct proof-of-concept experiments that support these results. We see this work as contributing towards a theory behind algorithms for human-robot interaction."

links:
  - name: ArXiv Preprint
    url: https://arxiv.org/abs/1903.04359

url_pdf: "https://arxiv.org/pdf/1903.04359.pdf"
url_code: "https://github.com/Chanlaw/assistive-bandits"
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---
