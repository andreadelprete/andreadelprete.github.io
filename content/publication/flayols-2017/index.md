---
title: Experimental Evaluation of Simple Estimators for Humanoid Robots
authors:
- Thomas Flayols
- Andrea Del Prete
- Patrick Wensing
- Alexis Mifsud
- Mehdi Benallegue
- Olivier Stasse
date: '2017-01-01'
publishDate: '2023-12-31T13:16:02.806608Z'
publication_types:
- paper-conference
publication: '*IEEE International Conference on Humanoid Robots (Humanoids)*'
abstract: This paper introduces and evaluates a family of new simple estimators to
  reconstruct the pose and velocity of the floating base. The estimation of the floating-base
  state is a critical challenge to whole-body control methods that rely on full-state
  information in high-rate feedback. Although the kinematics of grounded limbs may
  be used to estimate the pose and velocity of the body, modelling errors from ground
  irregularity, foot slip, and structural flexibilities limit the utility of estimation
  from kinematics alone. These difficulties have motivated the development of sensor
  fusion methods to augment body-mounted IMUs with kinematic measurements. Existing
  methods often rely on extended Kalman filtering, which lack convergence guarantees
  and may present difficulties in tuning. This paper proposes two new simplifications
  to the floating-base state estimation problem that make use of robust off-the-shelf
  orientation estimators to bootstrap development. Experiments for in-place balance
  and walking with the HRP-2 show that the simplifications yield results on par with
  the accuracy reported in the literature for other methods. As further benefits,
  the structure of the proposed estimators prevents divergence of the estimates, simplifies
  tuning, and admits efficient computation. These benefits are envisioned to help
  accelerate the development of baseline estimators in future humanoids.
links:
- name: URL
  url: https://hal.archives-ouvertes.fr/hal-01574819
---
