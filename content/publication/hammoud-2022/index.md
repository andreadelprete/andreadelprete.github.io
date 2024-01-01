---
title: Exponential integration for efficient and accurate multibody simulation with
  stiff viscoelastic contacts
authors:
- Bilal Hammoud
- Luca Olivieri
- Ludovic Righetti
- Justin Carpentier
- Andrea Del Prete
date: '2022-01-01'
publishDate: '2023-12-31T13:16:02.663939Z'
publication_types:
- article-journal
publication: '*Multibody System Dynamics*'
doi: 10.1007/s11044-022-09818-z
abstract: The simulation of multibody systems with frictional contacts is a fundamental
  tool for many fields, such as robotics, computer graphics, and mechanics. Hard frictional
  contacts are particularly troublesome to simulate because they make differential
  equations stiff, calling for computationally demanding implicit integration schemes.
  We suggest to tackle this issue by using exponential integrators, a long-standing
  class of integration schemes (first introduced in the 1960s) that in recent years
  has enjoyed a resurgence of interest. This scheme can be applied to multibody systems
  subject to stiff viscoelastic contacts, leading to integration errors similar to
  implicit Euler, but at much lower computational costs (between 2 to 100 times faster).
  In our tests with quadruped and biped robots, our method demonstrated a stable behavior
  with large time steps (10 ms) and stiff contacts (10 5 N/m). Its excellent properties,
  especially for fast and coarse simulations, make it a valuable candidate for many
  applications in robotics, such as simulation, model predictive control, reinforcement
  learning, and controller design.
tags:
- Contact simulation
- Exponential integrators
- Robotics
- Spring-damper
links:
- name: arXiv
  url: https://arxiv.org/pdf/2101.06846.pdf
---
