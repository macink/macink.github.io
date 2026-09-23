---
layout: default
title: Projects
permalink: /projects/
---

The are my current main projects:

## Suppressing Incoherent Background in Exclusive Diffractive eA Processes
This research aims to separate coherent and incoherent production in the momentum transfer distribution from exclusive vector meson production. Determining the fraction of coherent events is essential for nuclear imaging to study phenomena such as the onset of gluon saturation. 

*Methods:*
- Utilizing the electron beam polarization
  - Polarized electron beam provides a controllable spin axis
  - By projecting the event kinematics onto this axis, we can construct a spin‑dependent observable (&psi;) that respond differently to coherent and incoherent events
- Implementing a spin‑projection method to enhance coherent sensitivity
  - Project the virtual photon’s polarization direction into the vector meson decay frame
  - This makes the cos(2&psi;) modulation an experimentally accessible signature of coherent production
- Extracting the coherent fraction through \|t\|‑binned modulation amplitudes
  - By measuring the amplitude of the cos(2&psi;) term in each \|t\| bin, we obtain an estimate of the coherent fraction of events

## Investigating Spin Transfer and Projective Techniques in ep Events
This work establishes the baseline behavior of spin‑dependent observables in ep systems. Benchmarking these measurements will be crucial for understanding eA physics.

*Methods:*
- Validating the projected‑\|t\| method on ep data
  - Using the technique demonstrated in Phys. Lett. B (DOI: 10.1016/j.physletb.2026.140585), we can test whether the projected‑\|t\| reconstruction reliably recovers the true momentum‑transfer distribution in ep events
  - This serves as a control sample for the eA case
- Studying how spin transfer affects exclusive final states
  - Analyze how longitudinal vs. transverse electron polarization modifies the angular distribution of exclusive vector meson production
  - Understand how this differs between coherent and incoherent regimes

## Developing Machine Learning Algorithms to Resolve the Momentum Transfer Distribution in eA Collisions
This research aims to build ML models that can reconstruct the true \|t\| distribution from detector smeared distributions.

*Methods:*
- Architectures that incorporate phase‑space dependent detector resolution
  - We embed the event‑level resolution into the model using FiLM conditioning
  - This prevents the network from memorizing smeared patterns and forces it to learn the underlying physics
- Using Fourier features to stabilize learning across dynamic ranges
  - Fourier encoding improves the model’s ability to represent sharp structures
  - This is crucial for diffractive processes where the distribution is oscillatory
