---
title: Optimization and Learning for Robot Control (PhD)
summary: A 15-hour course for PhD students focusing on modern optimal control and reinforcement learning techniques for robot control
tags:
  - Trajectory Optimization
  - Reinforcement Learning
  - Optimal Control
date: '2026-01-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

# image:
#   caption: None
#   focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: 'https://github.com/andreadelprete/orc'
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

##### SIDRA PhD School, 2026, Bertinoro, Italy

This 15-hour course is intended for PhD students and researchers and addresses the control of robotic systems, with a particular focus on approaches based on optimization and machine/reinforcement learning. Following a concise review of the fundamental principles of robot modeling and numerical optimization, the course will cover a variety of control techniques, including established methods for trajectory optimization and reinforcement learning. The final part of the course will be devoted to recent advances that combine these two paradigms. The proposed methods will be introduced both theoretically, through board-based lectures, and practically, through Python implementations centered on representative robotic applications such as manipulators, vehicles, and legged robots.

# Content 

##### Trajectory Optimization (TO)

* Review of robot dynamics modeling
* Review of gradient-based numerical optimization
* Direct methods for TO
* Model Predictive Control: recursive feasibility, stability, warm-start
* Use-case: obstacle avoidance
* Use-case: minimum-time optimal control

##### Reinforcement Learning (RL)

* Dynamic Programming: Value and policy iteration
* Monte Carlo and Temporal Difference learning
* Q-learning and SARSA
* Deep Q-Network and Deep Deterministic Policy Gradient

##### Combining TO and RL

* Sequential approaches: TO imitation, RL-supported TO
* Coupled approaches: coupled TO imitation, TO inside RL
* Architectures for TO inside RL: pre-policy, post-policy, residual policy

## Prerequisite
Students should have consolidated knowledge in

- Mechanics: Newtonian dynamics in 3D, homogeneous transformation for expressing vectors in different frames
- Mathematics: linear algebra (eigenvalues, eigenvectors, rank, nullspace), multivariable differential calculus
- Systems: state space representation, stability criteria for linear dynamical systems
- Programming: object-oriented programming (if-else, for, while, objects, polymorphism)