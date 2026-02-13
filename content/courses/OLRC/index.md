---
title: Optimization and Learning for Robot Control
summary: A 48-hour course for master students focusing on modern optimal control and reinforcement learning techniques for robot control
tags:
  - Trajectory Optimization
  - Reinforcement Learning
  - Optimal Control
date: '2020-01-01T00:00:00Z'

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
url_slides: 'https://drive.google.com/drive/folders/1k8dJvZjvu2eXAbc_voIXrQdjUfSksdFz?usp=sharing'
url_video: 'https://www.youtube.com/watch?v=vWg4SMDJDQ0&list=PL4nPbSX5VFGjA3ZSbdtcVEeUSIzYeF0Xw'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

##### Industrial Engineering Department, since 2020, University of Trento (Trento, Italy)

A 48-hour course for master students. 
This course focuses on control of robotic systems, with special attention to methods based on optimization techniques. After reviewing the basic principles of robot modeling and numerical optimization, students will learn different control techniques, from the simplest and most well-known, to the most recent and advanced. Methods will be first studied in theory, and then implemented in simulation (with the Python language) to gain practical experience. The lab sessions will focus on industrial manipulators and legged robots, but most of the studied methods could also be applied to flying and wheeled robots. After completing the course, students will be able to:
- understand the working principles of several control algorithms for robotic systems
- choose the appropriate approach(es) to control a specific system for a given target application
- implement, tune, and test control algorithms with the Python language


Using the links above you can find videos and slides of all the lectures recorded in 2022. Since 2023, the suggested environment for coding has switched to docker. Installation instructions can be found in the Github repo of the course (link above).

# Content 
The course includes approximately 32 hours of lectures (program below) and 16 hours of programming exercises.

##### Reactive Control

* Review of robot kinematics, Jacobian, statics, Lagrangian dynamics
* Joint motion control: PID, PD+gravity compensation, inverse dynamics
* Operational-space control
* Quadratic-Programming based control: underactuated systems, rigid contacts, multi-task control

##### Optimal Control

* Overview: global vs local approaches
* Direct methods: single shooting, multiple shooting and collocation
* Model Predictive Control: recursive feasibility, stability
* Use-case: obstacle avoidance
* Use-case: minimum-time optimal control

##### Reinforcement Learning

* Markov Decision Processes
* Dynamic Programming: Value and policy iteration
* Prediction with Monte Carlo and Temporal Difference learning
* Q-learning and SARSA
* Value function approximation and Deep Q-Network
* Policy gradient methods


## Prerequisite
Students should have consolidated knowledge in

- Mechanics: Newtonian dynamics in 3D, homogeneous transformation for expressing vectors in different frames
- Mathematics: linear algebra (eigenvalues, eigenvectors, rank, nullspace), multivariable differential calculus
- Systems: state space representation, stability criteria for linear dynamical systems
- Programming: object-oriented programming (if-else, for, while, objects, polymorphism)