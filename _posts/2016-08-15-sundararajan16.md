---
title: A Genetic Algorithm for Learning Parameters in Bayesian Networks using Expectation
  Maximization
abstract: Expectation maximization (EM) is a popular algorithm for parameter estimation
  in situations with incomplete data. The EM algorithm has, despite its popularity,
  the disadvantage of often converging to local but non-global optima. Several techniques
  have been proposed to address this problem, for example initializing EM from multiple
  random starting points and then selecting the run with the highest likelihood. Unfortunately,
  this method is computationally expensive. In this paper, our goal is to reduce computational
  cost while at the same time maximizing likelihood. We propose a Genetic Algorithm
  for Expectation Maximization (GAEM) for learning parameters in Bayesian networks.
  GAEM combines the global search property of a genetic algorithm with the local search
  property of EM. We prove GAEM’s global convergence theoretically. Experimentally,
  we show that GAEM provides significant speed-ups since it tends to select more fit
  individuals, which converge faster, as parents for the next generation. Specifically,
  GAEM converges 1.5 to 7 times faster while producing better log-likelihood scores
  than the traditional EM algorithm.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: sundararajan16
month: 0
tex_title: A Genetic Algorithm for Learning Parameters in {B}ayesian Networks using
  Expectation Maximization
firstpage: 511
lastpage: 522
page: 511-522
sections: 
author:
- given: Priya Krishnan
  family: Sundararajan
- given: Ole J.
  family: Mengshoel
date: 2016-08-15
address: Lugano, Switzerland
publisher: PMLR
container-title: Proceedings of the Eighth International Conference on Probabilistic
  Graphical Models
volume: '52'
genre: inproceedings
issued:
  date-parts:
  - 2016
  - 8
  - 15
pdf: http://proceedings.mlr.press/v52/sundararajan16.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
