---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Machine learning using approximate inference : Variational and sequential
  Monte Carlo methods'
subtitle: ''
summary: ''
authors:
- Christian A. Naesseth
tags: []
categories: []
date: '2018-01-01'
lastmod: 2020-12-19T12:38:42-05:00
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
publishDate: '2020-12-19T17:38:41.993090Z'
publication_types:
- '7'
abstract: 'Automatic decision making and pattern recognition under uncertainty are difficult tasks that are ubiquitous in our everyday life. The systems we design, and technology we develop, requires us to coherently represent and work with uncertainty in data. Probabilistic models and probabilistic inference gives us a powerful framework for solving this problem. Using this framework, while enticing, results in difficult-to-compute integrals and probabilities when conditioning on the observed data. This means we have a need for approximate inference, methods that solves the problem approximately using a systematic approach. In this thesis we develop new methods for efficient approximate inference in probabilistic models.

There are generally two approaches to approximate inference, variational methods and Monte Carlo methods. In Monte Carlo methods we use a large number of random samples to approximate the integral of interest. With variational methods, on the other hand, we turn the integration problem into that of an optimization problem. We develop algorithms of both types and bridge the gap between them.

First, we present a self-contained tutorial to the popular sequential Monte Carlo (SMC) class of methods. Next, we propose new algorithms and applications based on SMC for approximate inference in probabilistic graphical models. We derive nested sequential Monte Carlo, a new algorithm particularly well suited for inference in a large class of high-dimensional probabilistic models. Then, inspired by similar ideas we derive interacting particle Markov chain Monte Carlo to make use of parallelization to speed up approximate inference for universal probabilistic programming languages. After that, we show how we can make use of the rejection sampling process when generating gamma distributed random variables to speed up variational inference. Finally, we bridge the gap between SMC and variational methods by developing variational sequential Monte Carlo, a new flexible family of variational approximations.'
publication: ''
url_pdf: http://urn.kb.se/resolve?urn=urn:nbn:se:liu:diva-152647
---
