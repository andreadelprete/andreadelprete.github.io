---
title: Globally Optimal and Safe Robot Control

event: IEEE RAS Technical Committee on Model Based Optimization for Robotics Seminars
event_url: https://www.tcoptrob.org/

location: online 

summary: Invited online talk for the IEEE RAS Technical Committee on Model Based Optimization for Robotics 
###abstract: 

### Talk start and end times.
date: '2024-12-01T13:00:00Z'
all_day: false

publishDate: '2026-02-13T00:00:00Z'

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Screenshot from the video'
  focal_point: Right

url_slides: 'talks/202412_tc_globally_optimal_safe_robot_control.pdf'
url_video: 'https://www.youtube.com/watch?v=BQR0lANoJzI'


---

In recent years, advanced data-driven control methods are unlocking the potential of complex robotics systems, and we can expect this trend to continue at an exponential rate in the near future. However, these methods present two major shortcomings. First, their training process is excessively data hungry and strongly dependent on the exploration strategy. Second, the resulting policies cannot ensure constraint satisfaction (i.e. safety). In this talk I will discuss how we are using tools from optimal control to address these two issues.

First, I will present "Continuous Actor Critic with Trajectory Optimization" (CACTO), a novel algorithm that combines Trajectory Optimization (TO) and Reinforcement Learning (RL). CACTO learns a control policy via TO-guided RL policy search. Our method is validated on several non-convex problems with different robotic systems. Our results show the great capabilities of CACTO in escaping local minima, while being more sample-efficient than DDPG and PPO. To address the issue of safety, a well-known tool is the control-invariant set (a.k.a. safe set). Unfortunately, for nonlinear systems, such sets can only be approximated. I will present some novel MPC schemes that guarantee safety under weaker assumptions than classic methods. Our key idea is to make the safe-set constraint move backward (i.e. recede) over the horizon. We evaluated our approaches on simulated robot manipulators, empirically demonstrating that they lead to less constraint violations, while retaining good tracking cost and computation times.