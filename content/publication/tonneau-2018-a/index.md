---
title: An Efficient Acyclic Contact Planner for Multiped Robots
authors:
- Steve Tonneau
- Andrea Del Prete
- Julien Pettre
- Chonhyon Park
- Dinesh Manocha
- Nicolas Mansard
date: '2018-01-01'
publishDate: '2023-12-31T13:16:02.769469Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Robotics*'
doi: 10.1109/TRO.2018.2819658
abstract: 'We present a framework capable of producing contact plans describing complex
  multiped motions (including humanoid): standing up, climbing stairs using a handrail,
  crossing rubble and getting out of a car. Our framework answers a need demonstrated
  at the Darpa Robotics Challenge, where the lack of an automatic acyclic contact
  planner was recognized a major issue. Our novel key idea is the reachability condition.
  Informally, it verifies that the root configuration of a robot is “close, but not
  too close” from obstacles: close to allow contact creation, not too close to avoid
  collision. With this approximation of the space of admissible root configurations
  we decompose the hard contact planning problem into simpler sub-problems: first,
  to plan a guide path for the root without considering the whole-body configuration;
  then, to generate a discrete sequence of whole-body configurations in static equilibrium
  along this path. The reachability condition turns the high-dimensional computation
  of the guide into a collision checking problem, solved in less than a few seconds.
  Then a deterministic contact selection algorithm tackles the combinatorial issue
  of generating of a discrete sequence along the guide path. Several innovations make
  it computationally efficient: a criterion for verifying static equilibrium, and
  a set of heuristics used to enforce desirable properties on the configuration. Our
  approach results from the pragmatic choice of favoring efficiency over exhaustiveness,
  justified empirically: in a few seconds, with satisfying success rates, we generate
  complex contact plans for various scenarios and robots, namely HRP-2, HyQ, and a
  dexterous hand.'
tags:
- Centroidal dynamics
- Collision avoidance
- Complexity theory
- Foot
- Legged locomotion
- Manifolds
- Planning
- humanoid robots
- legged robots
- motion planning
- multicontact locomotion
links:
- name: arXiv
  url: https://arxiv.org/abs/arXiv:1508.04886v1
---
