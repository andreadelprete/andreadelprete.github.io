---
title: MyCobot Identification
date: 2026-04-02
math: true
image:
  placement: 2
  caption: ''
---

# MyCobot280 Identification

Goal: to identify the dynamic behavior of the robot manipulators MyCobot280.

## Description

The robot manipulators MyCobot280 accept only joint position commands as control inputs. 
Internally, these position commands are used as targets to generate interpolating trajectories, which are then internally used as references for the low-level motor controllers. 

In order to accurately simulate the behavior of the robot, we would like to identify this interpolation procedure. We can do this by collecting data on the robot and then trying to fit different trajectories to the collected data points. My current guess is that these are minimum-time trajectories with bounded velocity and acceleration.
To identify the maximum velocity for each joint, we can command them to move a long distance and observe their maximum velocity.


### Expected results

At the end of this work, the student should have produced:

- python code implementing an accurate simulator of the robot
- a document describing in detail the work, presenting and discussing the collected data, comparing the simulated behavior with the real robot data
- a video showing the behavior of the robot in simulation
- a video showing the behavior of the real robot
