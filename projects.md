---
layout: default
title: Projects
permalink: /projects/
---

Here are my current main projects:

## Suppressing Incoherent Background in Exclusive Diffractive eA Processes
This research aims to separate coherent and incoherent production in the momentum transfer distribution (\|t\|) from exclusive vector meson (VM) production. Determining the fraction of coherent events is essential for nuclear imaging to study phenomena such as the onset of gluon saturation. 

*Methods:*
- Utilizing the electron beam polarization
  - Polarized electron beam provides a controllable spin axis
  - Spin transfer propagates from virtual photon to VM decay daughter
  - By projecting the event kinematics onto this axis, we can construct a spin‑dependent observable that we expect to respond differently to coherent and incoherent events
 
## Investigating Spin Transfer and Projective Techniques in ep Events
This work establishes the behavior of spin‑dependent observables in ep systems. Benchmarking these measurements will be crucial for understanding eA physics.

*Methods:*
- Validating the projected‑\|t\| method on ep data
  - Using the technique demonstrated in Phys. Lett. B (DOI: 10.1016/j.physletb.2026.140585), we can test whether the projected‑\|t\| reconstruction reliably resolves the \|t\| distribution in ep collisions
  - This serves as a control sample for the eA case
- Studying how spin transfer affects exclusive final states
  - Analyze how longitudinal vs. transverse electron polarization modifies the angular distribution of exclusive VM production
  - Understand how this differs between coherent and incoherent regimes

## Developing Machine Learning Algorithms to Resolve the Momentum Transfer Distribution in eA Collisions
This research aims to build ML models that can reconstruct the true \|t\| distribution from detector-smeared distributions.

*Methods:*
- Develop architectures that incorporate phase‑space dependent detector resolution
  - Embed the event‑level resolution into the model using FiLM conditioning
  - This prevents the network from memorizing smeared patterns and forces it to learn the underlying physics
- Using Fourier features to stabilize learning across dynamic ranges
  - Fourier encoding improves the model’s ability to represent sharp structures
  - This is crucial for diffractive processes where the distribution is oscillatory
