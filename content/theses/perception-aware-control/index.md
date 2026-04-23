---
title: Bachelor Thesis
date: 2026-04-02
math: true
image:
  placement: 2
  caption: 'Image credit: [**John Moeses Bauan**](https://unsplash.com/photos/OGZtQF8iC0g)'
---

# Perception-Aware Control

Goal: control a robot manipulator while ensuring that the target remains within the field of view (FoV) of the camera mounted on the end-effector.

## Description

The starting point is to control the robot with velocity-level differential inverse kinematics, i.e. using a Jacobian pseudo-inverse and sending joint velocity commands to the robot. 
Then we need to add another task that consists in maintaining the target inside the field of view of the camera. This task is actually more important than the other, but it needs only to be active when the target has reached the limits of the camera's FoV. Whenever that happens, we should consider as primary task moving the robot so that the target moves towards the center of the FoV. This task takes at most 2 DoF. The secondary task can be moving the end-effector towards the target.
If instead the target is not at the boundary of the FoV we can simply perform the task of moving the end-effector towards the target.

### Projecting the target to the 2D image space

To detect whether the target is on the boundary of the FoV we have to project it to 2D image space. Moreover, to implement the FoV task we must compute the Jacobian associated to the position of the target in 2D image space, which depends on both the position and orientation of the camera.

### Expected results

At the end of this work, the student should have produced:

- python code implementing the described control framework
- a document describing in detail the work, including the mathematics behind it
- a video showing the behavior of the robot in simulation
- a video showing the behavior of the real robot
