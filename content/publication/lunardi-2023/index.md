---
title: Reference-free Model Predictive Control for Quadrupedal Locomotion
authors:
- Gianni Lunardi
- Thomas Corbères
- Carlos Mastalli
- Nicolas Mansard
- Thomas Flayols
- Steve Tonneau
- Andrea Del Prete
date: '2023-01-01'
publishDate: '2024-01-02T20:41:43.915784Z'
publication_types:
- article-journal
publication: '*IEEE Access*'
abstract: Full-dynamics model predictive control (MPC) has recently been applied to quadrupedal locomotion in semi-unstructured environments. These advances have been fueled by the availability of efficient trajectory optimization (TO) algorithms and inexpensive computational power. The main advantages of full-dynamics MPC are (i) enabling complex locomotion manoeuvres, (ii) considering actuation limits, and (iii) improving robot stability. However, to make the TO problem sufficiently simple to be solved at run time, reference swing foot trajectories are usually tracked in the MPC formulation. These trajectories are often computed independently of the motion of the joints, limiting the approach generality and capability. To address this limitation, we present a full-dynamics MPC formulation that does not require reference swing-foot trajectories, featuring a novel cost function targeting swing foot motion and considering environmental information. Removing the need for reference swing foot trajectories, our approach can also automatically adjust footstep locations, as long as the contact surfaces are predefined. We have validated our MPC formulation through simulations and experiments on the ANYmal B robot. Our approach has similar computational efficiency to state-of-the-art formulations, while displaying superior push-recovery capabilities on various terrains.
doi: 10.1109/ACCESS.2023.3345157
links:
- name: URL
  url: https://ieeexplore.ieee.org/abstract/document/10366250
- name: Video
  url: https://www.youtube.com/watch?v=3lK3TxqPrjw
---
