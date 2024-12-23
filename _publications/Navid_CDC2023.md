---
title: "Data-Driven Reachability Analysis of Stochastic Dynamical Systems with Conformal Inference"
collection: publications
permalink: /publication/Navid_CDC2023
excerpt: ""
date: 2023-12-13
venue: '2023 62nd IEEE Conference on Decision and Control (CDC)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10384213'
citation: 'Hashemi, Navid, Xin Qin, Lars Lindemann, and Jyotirmoy V. Deshmukh. "Data-driven reachability analysis of stochastic dynamical systems with conformal inference." In 2023 62nd IEEE Conference on Decision and Control (CDC), pp. 3102-3109. IEEE, 2023.'
---


We consider data-driven reachability analysis of discrete-time stochastic dynamical systems using conformal inference. We assume that we are not provided with a symbolic representation of the stochastic system, but instead have access to a dataset of K-step trajectories. The reachability problem is to construct a probabilistic flowpipe such that the probability that a K-step trajectory can violate the bounds of the flowpipe does not exceed a user-specified failure probability threshold. The key ideas in this paper are: (1) to learn a surrogate predictor model from data, (2) to perform reachability analysis using the surrogate model, and (3) to quantify the surrogate model's incurred error using conformal inference in order to give probabilistic reachability guarantees. We focus on learning-enabled control systems with complex closed-loop dynamics that are difficult to model symbolically, but where state transition pairs can be queried, e.g., using a simulator. We demonstrate the applicability of our method on examples from the domain of learning-enabled cyber-physical systems.
