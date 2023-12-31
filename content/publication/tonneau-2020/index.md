---
title: 'SL1M: Sparse L1-norm Minimization for contact planning on uneven terrain'
authors:
- Steve Tonneau
- Daeun Song
- Pierre Fernbach
- Nicolas Mansard
- Michel Taix
- Andrea Del Prete
date: '2020-01-01'
publishDate: '2023-12-31T13:16:02.754449Z'
publication_types:
- paper-conference
publication: '*IEEE International Conference on Robotics and Automation*'
abstract: One of the main challenges of planning legged locomotion in complex environments
  is the combinatorial contact selection problem. Recent contributions propose to
  use integer variables to represent which contact surface is selected, and then to
  rely on modern mixed-integer (MI) optimization solvers to handle this combinatorial
  issue. To reduce the computational cost of MI, we exploit the sparsity properties
  of L1 norm minimization techniques to relax the contact planning problem into a
  feasibility linear program. Our approach accounts for kinematic reachability of
  the center of mass (COM) and of the contact effectors. We ensure the existence of
  a quasi-static COM trajectory by restricting our plan to quasi-flat contacts. For
  planning 10 steps with less than 10 potential contact surfaces for each phase, our
  approach is 50 to 100 times faster that its MI counterpart, which suggests potential
  applications for online contact re-planning. The method is demonstrated in simulation
  with the humanoid robots HRP-2 and Talos over various scenarios.
links:
- name: arXiv
  url: https://arxiv.org/abs/1909.09044
- name: URL
  url: http://arxiv.org/abs/1909.09044
---
