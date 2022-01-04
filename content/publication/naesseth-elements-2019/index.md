---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Elements of Sequential Monte Carlo
subtitle: ''
summary: ''
authors:
- Christian A. Naesseth
- Fredrik Lindsten
- Thomas B. Schön
tags: []
categories: []
date: '2019-11-01'
lastmod: 2020-12-19T12:36:28-05:00
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
publishDate: '2020-12-19T17:36:28.280935Z'
publication_types:
- '2'
abstract: 'A core problem in statistics and probabilistic machine learning is to compute probability distributions and expectations. This is the fundamental problem of Bayesian statistics and machine learning, which frames all inference as expectations with respect to the posterior distribution. The key challenge is to approximate these intractable expectations. In this tutorial, we review sequential Monte Carlo (SMC), a random-samplingbased class of methods for approximate inference. First, we explain the basics of SMC, discuss practical issues, and review theoretical results. We then examine two of the main user design choices: the proposal distributions and the so called intermediate target distributions. We review recent results on how variational inference and amortization can be used to learn efficient proposals and target distributions. Next, we discuss the SMC estimate of the normalizing constant, how this can be used for pseudo-marginal inference and inference evaluation. Throughout the tutorial we illustrate the use of SMC on various models commonly used in machine learning, such as stochastic recurrent neural networks, probabilistic graphical models, and probabilistic programs.'
publication: '*Foundations and Trends® in Machine Learning*'
url_pdf: https://www.nowpublishers.com/article/Details/MAL-074
doi: 10.1561/2200000074
---
