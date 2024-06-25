---
title: 'CACTO-SL: Using Sobolev Learning to improve Continuous Actor-Critic with Trajectory
  Optimization'
authors:
- Elisa Alboni
- Gianluigi Grandesso
- Gastone P. Rosati Papini
- Justin Carpentier
- Andrea Del Prete
date: '2024-01-01'
publishDate: '2024-01-02T20:41:43.943525Z'
publication_types:
- paper-conference
publication: '*Learning for Dynamics and Control Conference*'
abstract: Trajectory Optimization (TO) and Reinforcement Learning (RL) are powerful and complementary tools to solve optimal control problems. On the one hand, TO can efficiently compute locally- optimal solutions, but it tends to get stuck in local minima if the problem is not convex. On the other hand, RL is typically less sensitive to non-convexity, but it requires a much higher computational effort. Recently, we have proposed CACTO (Continuous Actor-Critic with Trajectory Optimization), an algorithm that uses TO to guide the exploration of an actor-critic RL algorithm. In turns, the policy encoded by the actor is used to warm-start TO, closing the loop between TO and RL. In this work, we present an extension of CACTO exploiting the idea of Sobolev learning. To make the training of the critic network faster and more data efficient, we enrich it with the gradient of the Value function, computed via a backward pass of the differential dynamic programming algorithm. Our results show that the new algorithm is more efficient than the original CACTO, reducing the number of TO episodes by a factor ranging from 3 to 10, and consequently the computation time. Moreover, we show that CACTO-SL helps TO to find better minima and to produce more consistent results.
tags:
- global optimization
- reinforcement learning
- sobolev learning
- trajectory optimization
links:
- name: arXiv
  url: https://arxiv.org/abs/arXiv:2312.10666v1
- name: Video
  url: https://www.youtube.com/watch?v=zAv8dP8itpM&feature=youtu.be
- name: Code
  url: https://github.com/gianluigigrandesso/cacto
---
