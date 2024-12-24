---
title: "A Neurosymbolic Approach to the Verification of Temporal Logic Properties of Learning-enabled Control Systems"
collection: publications
permalink: /publication/Navid_ICCPS2023
excerpt: ''
date: 2023-05-01
venue: 'ICCPS 2023: Proceedings of the ACM/IEEE 14th International Conference on Cyber-Physical Systems (with CPS-IoT Week 2023)'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3576841.3585928'
citation: 'Hashemi, Navid, Bardh Hoxha, Tomoya Yamaguchi, Danil Prokhorov, Georgios Fainekos, and Jyotirmoy Deshmukh. "A neurosymbolic approach to the verification of temporal logic properties of learning-enabled control systems." In Proceedings of the ACM/IEEE 14th International Conference on Cyber-Physical Systems (with CPS-IoT Week 2023), pp. 98-109. 2023.'
---

Signal Temporal Logic (STL) has become a popular tool for expressing formal requirements of Cyber-Physical Systems (CPS). The problem of verifying STL properties of neural network-controlled CPS remains a largely unexplored problem. In this paper, we present a model for the verification of Neural Network (NN) controllers for general STL specifications using a custom neural architecture where we map an STL formula into a feed-forward neural network with ReLU activation. In the case where both our plant model and the controller are ReLU-activated neural networks, we reduce the STL verification problem to reachability in ReLU neural networks. We also propose a new approach for neural network controllers with general activation functions; this approach is a sound and complete verification approach based on computing the Lipschitz constant of the closed-loop control system. We demonstrate the practical efficacy of our techniques on a number of examples of learning-enabled control systems.
