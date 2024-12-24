---
title: "Certifying Incremental Quadratic Constraints for Neural Networks via Convex Optimization"
collection: publications
permalink: /publication/Navid_L4DC
excerpt: ''
date: 2021-05-01
venue: 'Proceedings of the 3rd Conference on Learning for Dynamics and Control, PMLR 144:842-853, 2021.'
paperurl: 'https://proceedings.mlr.press/v144/hashemi21a.html'
citation: 'Hashemi, Navid, Justin Ruths, and Mahyar Fazlyab. "Certifying incremental quadratic constraints for neural networks via convex optimization." Learning for Dynamics and Control. PMLR, 2021.'
---

Abstracting neural networks with constraints they impose on their inputs and outputs can be very useful in the analysis of neural network classifiers and to derive optimization-based algorithms for certification of stability and robustness of feedback systems involving neural networks. In this paper, we propose a convex program, in the form of a Linear Matrix Inequality (LMI), to certify quadratic bounds on the map of neural networks over a region of interest. These certificates can capture several useful properties such as (local) Lipschitz continuity, one-sided Lipschitz continuity, invertibility, and contraction. We illustrate the utility of our approach in two different settings. First, we develop a semidefinite program to compute guaranteed and sharp upper bounds on the local Lipschitz constant of neural networks and illustrate the results on random networks as well as networks trained on MNIST. Second, we consider a linear time-invariant system in feedback with an approximate model predictive controller given by a neural network. We then turn the stability analysis into a semidefinite feasibility program and estimate an ellipsoidal invariant set for the closed-loop system.
