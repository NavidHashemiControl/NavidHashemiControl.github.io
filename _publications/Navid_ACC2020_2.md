---
title: "Gain design via LMIs to minimize the impact of stealthy attacks"
collection: publications
permalink: /publication/Navid_ACC2029_2
excerpt: ""
date: 2020-07-01
venue: '2020 American Control Conference (ACC)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9147884'
citation: 'Hashemi, Navid, and Justin Ruths. "Gain design via LMIs to minimize the impact of stealthy attacks." 2020 American Control Conference (ACC). IEEE, 2020.'
---

The goal of this paper is to design the gain matrices for estimate-based feedback to minimize the impact that falsified sensor measurements can have on the state of a stochastic linear time invariant system. Here we consider attackers that stay stealthy, by raising no alarms, to a chi-squared anomaly detector, thereby restricting the set of attack inputs within an ellipsoidal set. We design linear matrix inequalities (LMIs) to find a tight outer ellipsoidal bound on the convex set of states reachable due to the stealthy inputs (and noise). Subsequently considering the controller and estimator gains as design variables requires further linearization to maintain the LMI structure. Without a competing performance criterion, the solution of this gain design is the trivial uncoupling of the feedback loop (setting either gain to zero). Here we consider and convexify - an output constrained covariance (OCC) ∥H∥ 2 gain constraint on the non-attacked system. Through additional tricks to linearize the combination of these LMI constraints, we propose an iterative algorithm whose core is a combined convex optimization problem to minimize the state reachable set due to the attacker while ensuring a small enough ∥H∥ 2 gain during nominal operation.
