---
title: Zero Step Capturability for Legged Robots in Multicontact
authors:
- Andrea Del Prete
- Steve Tonneau
- Nicolas Mansard
date: '2018-01-01'
publishDate: '2023-12-31T13:16:02.813975Z'
publication_types:
- article-journal
publication: '*IEEE Transaction on Robotics*'
doi: 10.1109/TRO.2018.2820687
abstract: The ability to anticipate a fall is fundamental for any robot that has to
  balance. Currently, fast fall-prediction algorithms only exist for simple models,
  such as the Linear Inverted Pendulum Model (LIPM), whose validity breaks down in
  multi-contact scenarios (i.e. when contacts are not limited to a flat ground). This
  paper presents a fast fall-prediction algorithm based on the point-mass model, which
  remains valid in multi-contact scenarios. The key assumption of our algorithm is
  that, in order to come to a stop without changing its contacts, a robot only needs
  to accelerate its center of mass in the direction opposite to its velocity. This
  assumption allows us to predict the fall by means of a convex optimal control problem,
  which we solve with a fast custom algorithm (less than 10 ms of computation time).
  We validated the approach through extensive simulations with the humanoid robot
  HRP-2 in randomly-sampled scenarios. Comparisons with standard LIPM-based methods
  demonstrate the superiority of our algorithm in predicting the fall of the robot,
  when controlled with a state-of-the-art balance controller. This work lays the foundations
  for the solution of the challenging problem of push recovery in multi-contact scenarios.
tags:
- Index Terms—Stability
- Legged Robots
- Multi-Contact
- Viability
links:
- name: URL
  url: https://hal.archives-ouvertes.fr/hal-01574687/document
---
