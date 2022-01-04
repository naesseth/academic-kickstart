---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Markovian Score Climbing: Variational Inference with KL(p||q)'
subtitle: ''
summary: ''
authors:
- Christian A. Naesseth
- Fredrik Lindsten
- David Blei
tags: []
categories: []
date: '2020-01-01'
lastmod: 2020-12-19T12:26:47-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: 'Example of the posterior variance estimated with MSC and a biased method (self-normalised IS/reweighting).'
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2020-12-19T17:26:47.620032Z'
publication_types:
- '1'
abstract: 'Modern variational inference (VI) uses stochastic gradients to avoid intractable expectations, enabling large-scale probabilistic inference in complex models. VI posits a family of approximating distributions q and then finds the member of that family that is closest to the exact posterior p. Traditionally, VI algorithms minimize the “exclusive Kullback-Leibler (KL)” KL(q||p), often for computational convenience. Recent research, however, has also focused on the “inclusive KL” KL(p||q), which has good statistical properties that makes it more appropriate for certain inference problems. This paper develops a simple algorithm for reliably minimizing the inclusive KL using stochastic gradients with vanishing bias. This method, which we call Markovian score climbing (MSC), converges to a local optimum of the inclusive KL. It does not suffer from the systematic errors inherent in existing methods, such as Reweighted Wake-Sleep and Neural Adaptive Sequential Monte Carlo, which lead to bias in their final estimates. We illustrate convergence on a toy model and demonstrate the utility of MSC on Bayesian probit regression for classification as well as a stochastic volatility model for financial data.'
publication: '*Advances in Neural Information Processing Systems 33*'
url_pdf: https://proceedings.neurips.cc//paper_files/paper/2020/hash/b20706935de35bbe643733f856d9e5d6-Abstract.html
---
