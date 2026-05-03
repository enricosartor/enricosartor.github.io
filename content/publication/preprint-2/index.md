---
title: "Optimal control of the coagulation-fragmentation equation"

date: 2026-04-15

authors:
  - coag-frag-control

publication_types: ["manuscript"]

publication: "*arXiv preprint*"

summary:  E. Sartor - April 2026

abstract: >
  We formulate and analyse an optimal control problem for the coagulation-fragmentation equation, where a scalar, time-dependent control modulates the coagulation rate by multiplying the coagulation kernel. The objective functional consists of a quadratic penalisation of the control and a terminal cost depending on the final size distribution. In a weighted  framework, we prove weak-to-weak continuity of the control-to-state map under perturbations of the coefficients and obtain existence of optimal controls by the direct method. We then establish -convergence of the corresponding cost functionals, providing stability of optimal controls and justifying truncation of unbounded kernels in the optimisation setting. For bounded coagulation kernels we show differentiability of the dynamics, derive an adjoint equation, and obtain a Pontryagin-type minimum principle. Lipschitz continuity of the gradient with respect to the control yields, at the continuous level, convergence of a projected-gradient algorithm with Armijo backtracking. A proof-of-concept finite-volume implementation is then used in a numerical study targeting the number of particles within a prescribed size window, demonstrating that a single low-dimensional actuator can effectively reshape an infinite-dimensional particle-size distribution.

links:
  - name: arXiv
    url: https://arxiv.org/abs/2604.13937
  - name: PDF
    url: paper.pdf

draft: false
share: false
---