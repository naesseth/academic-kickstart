---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Variational Sequential Monte Carlo
subtitle: ''
summary: ''
authors:
- Christian A. Naesseth
- Scott Linderman
- Rajesh Ranganath
- David Blei
tags: []
categories: []
date: '2018-03-01'
lastmod: 2020-12-19T12:34:21-05:00
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
publishDate: '2020-12-19T17:34:21.098459Z'
publication_types:
- '1'
abstract: 'Many recent advances in large scale probabilistic inference rely on variational methods. The success of variational approaches depends on (i) formulating a flexible parametric family of distributions, and (ii) optimizing the parameters to find the member of this family that most closely approximates the exact posterior. In this paper we present a new approximating family of distributions, the variational sequential Monte Carlo (VSMC) family, and show how to optimize it in variational inference. VSMC melds variational inference (VI) and sequential Monte Carlo (SMC), providing practitioners with flexible, accurate, and powerful Bayesian inference. The VSMC family is a variational family that can approximate the posterior arbitrarily well, while still allowing for efficient optimization of its parameters. We demonstrate its utility on state space models, stochastic volatility models for financial data, and deep Markov models of brain neural circuits.'
publication: '*International Conference on Artificial Intelligence and Statistics*'
url_pdf: http://proceedings.mlr.press/v84/naesseth18a.html
---
