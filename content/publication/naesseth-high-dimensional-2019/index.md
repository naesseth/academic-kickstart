---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: High-Dimensional Filtering Using Nested Sequential Monte Carlo
subtitle: ''
summary: ''
authors:
- Christian A. Naesseth
- Fredrik Lindsten
- Thomas B. Schön
tags:
- '"Adaptation models"'
- '"approximate Bayesian filtering"'
- '"approximate Bayesian inference"'
- '"backward simulation"'
- '"Bayes methods"'
- '"Biological system modeling"'
- '"Computational modeling"'
- '"exact approximation"'
- '"filtering theory"'
- '"high-dimensional filtering"'
- '"locally optimal proposal"'
- '"Monte Carlo methods"'
- '"nested sequential Monte Carlo"'
- '"Particle filtering"'
- '"Probabilistic logic"'
- '"Proposals"'
- '"Sequential Monte Carlo methods"'
- '"SMC proposal distribution"'
- '"spatio-temporal models"'
- '"state space models"'
- '"state-space methods"'
categories: []
date: '2019-08-01'
lastmod: 2020-12-19T12:36:33-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2020-12-19T17:36:33.066316Z'
publication_types:
- '2'
abstract: Sequential Monte Carlo (SMC) methods comprise one of the most successful
  approaches to approximate Bayesian filtering. However, SMC without a good proposal
  distribution can perform poorly, in particular in high dimensions. We propose nested
  sequential Monte Carlo, a methodology that generalizes the SMC framework by requiring
  only approximate, properly weighted, samples from the SMC proposal distribution,
  while still resulting in a correct SMC algorithm. This way, we can compute an “exact
  approximation” of, e.g., the locally optimal proposal, and extend the class of models
  for which we can perform efficient inference using SMC. We show improved accuracy
  over other state-of-the-art methods on several spatio-temporal state-space models.
publication: '*IEEE Transactions on Signal Processing*'
doi: 10.1109/TSP.2019.2926035
---
