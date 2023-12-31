---
title: 'VBOC: Learning the Viability Boundary of a Robot Manipulator using Optimal
  Control'
authors:
- Asia La Rocca
- Matteo Saveriano
- Andrea Del Prete
date: '2023-01-01'
publishDate: '2023-12-31T13:16:02.984164Z'
publication_types:
- article-journal
publication: '*IEEE Robotics and Automation Letters (RAL)*'
doi: 10.1109/LRA.2023.3313921
abstract: Safety is often the most important requirement in robotics applications.
  Nonetheless, control techniques that can provide safety guarantees are still extremely
  rare for nonlinear systems, such as robot manipulators. A well-known tool to ensure
  safety is the Viability kernel, which is the largest set of states from which safety
  can be ensured. Unfortunately, computing such a set for a nonlinear system is extremely
  challenging in general. Several numerical algorithms for approximating it have been
  proposed in the literature, but they suffer from the curse of dimensionality. This
  paper presents a new approach for numerically approximating the viability kernel
  of robot manipulators. Our approach solves optimal control problems to compute states
  that are guaranteed to be on the boundary of the set. This allows us to learn directly
  the set boundary, therefore learning in a smaller dimensional space. Compared to
  the state of the art on systems up to dimension 6, our algorithm resulted to be
  more than 2 times as accurate for the same computation time, or 6 times as fast
  to reach the same accuracy.
links:
- name: arXiv
  url: https://arxiv.org/abs/2305.07535
---
