---
title:  Combining Reinforcement Learning and Trajectory Optimization

event: Optimization for Robotics Summer School 2025
event_url: https://www.tcoptrob.org/summer-school-2025/

location: University of Patras, Greece

summary: Invited lecture at the Optimization for robotics summer school in Patras
#abstract: In this talk I cover recent methods from the state of the art that combine Reinforcement Learning and Trajectory Optimization techniques. 

# Talk start and end times.
date: '2025-07-16T13:00:00Z'
all_day: false

publishDate: '2026-02-13T00:00:00Z'

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Screenshot from the video'
  focal_point: Right

url_slides: 'talks/202507_patras_RL_and_TO.pdf'
url_video: 'https://www.youtube.com/watch?v=gP7v0fnUYdQ&list=PL6YqvXk7hmsk0jkSrJYq7x7oq7maJyqJ-&index=10'


---

Reinforcement Learning (RL) and Trajectory Optimization (TO) are two powerful yet complementary approaches to control and decision-making.

**Trajectory Optimization** is data-efficient, exploits dynamics derivatives, and naturally handles constraints. However, it can suffer from poor local minima and requires significant online computation.

**Reinforcement Learning**, on the other hand, is derivative-free, less sensitive to local minima, and enables fast policy execution at deployment. But it is typically data-inefficient and does not explicitly account for constraints.

The central question of this talk is:

> **How can we combine RL and TO to exploit the strengths of both?**

---

## A Taxonomy of RL–TO Architectures

The talk proposes a structured classification of approaches for combining RL and TO.

### 1. Sequential Approaches

#### TO → RL (Imitation)
- Use TO (e.g., MPC) to generate trajectories.
- Train a neural policy to imitate them.
- Removes online optimization at deployment.
- Cannot improve the original TO solution.

#### RL → TO (RL-Supported TO)
- Train an actor–critic.
- Use the actor to warm-start TO.
- Use the critic as a terminal cost.
- Guides TO toward better solutions.
- Does not improve RL efficiency.

---

### 2. Coupled TO Imitation

- TO and RL influence each other during training.
- Example: Guided Policy Search.
- TO produces trajectories that are easier for neural policies to represent.

---

### 3. TO Inside RL (Tight Integration)

This is the most powerful class of methods, which have the potential to speed-up RL training, speed-up TO online computation, while also guiding TO towards high-quality solutions. I discuss questions such as:
- **Where** should TO be introduced?
- **What** should be learned?
- Should TO solve the **same problem** as RL?

---

## CACTO: Continuous Actor-Critic with Trajectory Optimization

The final part of this talk presents **CACTO**, a tightly integrated actor–critic framework with derivative-based TO.

Core ideas:
- The actor generates a warm-start trajectory.
- TO refines it using dynamics derivatives.
- The critic is trained using TO’s cost-to-go.
- The actor is improved by minimizing the learned Q-function.
- Exploration occurs in the state space rather than the action space.

This creates a virtuous cycle:

- **TO improves RL sample efficiency.**
- **RL guides TO toward globally better solutions.**

Experiments on integrator systems, a car model, and a manipulator show that CACTO significantly improves the quality of TO solutions compared to random or standard RL warm-starts.

---

## Key Takeaways

- The architectural choice is fundamental when combining RL and TO.
- Warm-start learning is often more powerful than learning only a terminal cost.
- Dynamics derivatives (from TO) and global value shaping (from RL) are complementary.
- Tight integration improves both data efficiency and solution quality.

**Conclusion:**  
The most effective combination is not simple imitation or post-hoc refinement, but a tight coupling where RL and TO solve the same problem and guide each other toward globally optimal solutions.
