---
title: Optimization-based Control of Legged Robots
summary: A 12-hour course for PhD students about reactive control (TSID) and trajectory optimization for legged robots.
tags:
  - Trajectory Optimization
  - Optimal Control
  - Walking
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
url_slides: ''
url_video: 'https://www.youtube.com/playlist?list=PL4nPbSX5VFGg5Izt8hjyQ_2R8rdnn6qWg'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

##### Industrial Engineering Department, since 2019, University of Trento (Trento, Italy)

The course provides an overview of state-of-the-art techniques for the dynamic control of robotic systems, with a specific focus on legged robots (bipeds and quadrupeds) and robot manipulators. The course covers both theory and implementation, relying on the Python language and some existing libraries for robot visualization, multi-body dynamic computation, and trajectory optimization. 
The course is split in two parts, covering the following topics:

### PART 1
* Modeling of multi-body systems (recap)
* Modeling of legged robots
* Inverse-Dynamics Control (aka Computed Torque, or Feedback Linearization)
* Task-Space Inverse Dynamics (TSID), aka Operational-Space Control, Stack of Tasks
* QP-based TSID (with inequality constraints)
* Implementation exploiting an existing C++ library with Python bindings

### PART 2
* Linear Inverted Pendulum Model (LIPM)
* Center of Mass Trajectory Generation with LIPM
* Foot-step Planning
* Implementation in Python (exploiting existing library)
* Connecting Part 2 with Part 1 to get a legged robot walking in simulation

Following the link above you can find the videos of all the lectures (except the first one, which wasn't recorded).
Here you can find the slides:

- [Modeling](https://andreadelprete.github.io/teaching/2019_PhD_obrc/1_modeling.pdf)
- [Joint-Space Control](https://andreadelprete.github.io/teaching/2019_PhD_obrc/2_joint_space_control.pdf)
- [Joint-Space Control (implementation)](https://andreadelprete.github.io/teaching/2019_PhD_obrc/2b_tsid_implementation_joint_space.pdf)
- [Task-Space Control](https://andreadelprete.github.io/teaching/2019_PhD_obrc/3_task_space_control.pdf)
- [Task-Space Control (implementation)](https://andreadelprete.github.io/teaching/2019_PhD_obrc/4_tsid_implementation.pdf)
- [CoM Trajectory Optimization](https://andreadelprete.github.io/teaching/2019_PhD_obrc/5_com_traj_opt.pdf)