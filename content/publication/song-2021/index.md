---
title: Solving Footstep Planning as a Feasibility Problem Using L1-Norm Minimization
authors:
- Daeun Song
- Pierre Fernbach
- Thomas Flayols
- Andrea Del Prete
- Nicolas Mansard
- Steve Tonneau
- Young J. Kim
date: '2021-01-01'
publishDate: '2023-12-31T13:16:02.707085Z'
publication_types:
- article-journal
publication: '*IEEE Robotics and Automation Letters*'
doi: 10.1109/LRA.2021.3088797
abstract: One challenge of legged locomotion on uneven terrains is to deal with both
  the discrete problem of selecting a contact surface for each footstep and the continuous
  problem of placing each footstep on the selected surface. Consequently, footstep
  planning can be addressed with a Mixed Integer Program (MIP), an elegant but computationally
  demanding method, which can make it unsuitable for online planning. We reformulate
  the MIP into a cardinality problem, then approximate it as a computationally efficient
  ell 1-norm minimisation, called SL1M. Moreover, we improve the performance and convergence
  of SL1M by combining it with a sampling-based root trajectory planner to prune irrelevant
  surface candidates. Our tests on the humanoid Talos in four representative scenarios
  show that SL1M always converges faster than MIP. For scenarios when the combinatorial
  complexity is small (< 10 surfaces per step), SL1M converges at least two times
  faster than MIP with no need for pruning. In more complex cases, SL1M converges
  up to 100 times faster than MIP with the help of pruning. Moreover, pruning can
  also improve the MIP computation time. The versatility of the framework is shown
  with additional tests on the quadruped robot ANYmal.
tags:
- Humanoid and bipedal locomotion
- legged robots
- motion and path planning
links:
- name: arXiv
  url: https://arxiv.org/abs/2011.09772
---
