---
title: "Convex Optimization-based Policy Adaptation to Compensate for Distributional Shifts"
collection: publications
permalink: /publication/Navid_CDC2023_2
excerpt: ""
date: 2023-12-13
venue: '2023 62nd IEEE Conference on Decision and Control (CDC)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10383295'
citation: 'Hashemi, Navid, Justin Ruths, and Jyotirmoy V. Deshmukh. "Convex Optimization-based Policy Adaptation to Compensate for Distributional Shifts." 2023 62nd IEEE Conference on Decision and Control (CDC). IEEE, 2023.'
---

In many real-world cyber-physical systems, control designers often model the dynamics of the physical components using stochastic dynamical equations, and the design optimal control policies for the model. At any given time, a stochastic difference equation essentially models the distribution on next states conditioned on the state and controller action at that time. Due to shifts in this distribution, modeling assumptions on the stochastic dynamics made during initial control design may no longer be valid when the system is deployed in the real-world. In safety-critical systems, this can be particularly problematic; even if the system follows the designed control trajectory that was deemed safe and optimal, it may reach unsafe states due to the distribution shift. In this paper, we address the following problem: suppose we obtain an optimal control trajectory in the training environment, how do we ensure that in the real system this optimal trajectory is tracked with minimal error? In other words, we wish to adapt an optimal trained policy to distribution shifts in the environment. We show that this problem can be cast as a nonlinear optimization problem solvable using heuristic optimization methods. However, a convex relaxation of this problem allows us to learn policies that track the optimal trajectory with much better error performance and faster computation times. We demonstrate the efficacy of our approach on two different case studies: optimal path tracking using a Dubin's car model, and collision avoidance using both a linear and nonlinear model for adaptive cruise control
