---
layout: page
title: Research
permalink: /research/
#![Complex Systems](/figs/complex_systems.png)
---

## Complex Systems

<p align="center">
<img src="/figs/complex_systems.png">
</p>

Complex systems consist of devices with local dynamics and controllers that
are coupled by physical or cyber networks.
Such systems can exhibit elaborate collective behaviors, and are notoriously
challenging to analyze or control due to their large scale and complexity of
interactions.
Our research is centered around control, optimization, and dynamics of
complex systems, with particular focus in the following areas:

1. [Heterogeneous Ensemble Control](#heterogeneous-ensemble-control)
2. [Optimal and Distributed Control](#optimal-and-distributed-control)
3. [Nonlinear and Nonsmooth Stability Analysis](#nonlinear-and-nonsmooth-stability-analysis)
4. [Linear Control to Improve Nonlinear Robustness](#linear-control-to-improve-nonlinear-robustness)

## Heterogeneous Ensemble Control

<p align="center">
<img src="/figs/ensemble_1.png" width="600" height="498">
</p>

The goal of this work is to control a collection of heterogeneous
devices so that their aggregate dynamic behavior matches a desired dynamic
behavior as closely as possible, while satisfying local device limitations and
network dependent constraints.
This is a new but challenging problem due to nonconvexity and infinite
dimensionality of the optimization problem required to perform the control
design. Our approach combines a recent optimal control design technique based on
reparameterization with novel finite dimensional function space approximations
to arrive at tractable convex optimization problems for the design.
The methods have been applied to control a dynamic virtual power plant
consisting of a collection of distributed sources of renewable generation.

Relevant references:
1. P. D. Grontas, M. W. Fisher, and
F. Dörfler. Distributed and Constrained H2 Control Design via System
Level Synthesis and Dual Consensus ADMM. Submitted to *IEEE Conference
on Decision and Control*, 2022.
2. V. Häberle, M. W. Fisher,
E. Prieto-Araujo, and F. Dörfler. Control Design of Dynamic Virtual
Power Plants - An Adaptive Divide-and-Conquer Approach. *IEEE
Transactions on Power Systems*, To appear.

## Optimal and Distributed Control

<p align="center">
<img src="/figs/ensemble_2.png">
</p>

Optimal design of linear feedback controllers for devices distributed over a
network is a difficult task, which becomes increasingly complex when
devices are only able to communicate with their nearest neighbors.
This project focuses on developing novel optimal and distributed linear control
design techniques with provable closed-loop stability and convergence
guarantees.
Methods of design include approximations in complex function spaces, and
consensus-based distributed optimization, where each device has a local
estimate of global quantities which then achieve consensus.
	 
Relevant references:
1. M. W. Fisher, G. Hug, and
F. Dörfler. Approximation by Simple Poles – Part I: Density and
Geometric Convergence Rate in Hardy Space. Submitted to *IEEE
Transactions on Automatic Control*, 2022.
2. M. W. Fisher, G. Hug, and
F. Dörfler. Approximation by Simple Poles – Part II: System Level
Synthesis Beyond Finite Impulse Response. Submitted to *IEEE
Transactions on Automatic Control*, 2022.
3. P. D. Grontas,
M. W. Fisher, and F. Dörfler. Distributed and Constrained H2 Control
Design via System Level Synthesis and Dual Consensus ADMM. Submitted
to *IEEE Conference on Decision and Control*, 2022.

## Nonlinear and Nonsmooth Stability Analysis

<p align="center">
<img src="/figs/stability_1.png" width="500" height="356">`
</p>

Engineered systems naturally experience large disturbances which have the
potential to disrupt normal behavior.
This work aims to identify the regions for stability and recovery from
nonlinear and nonsmooth disturbances.
Hyperbolic dynamical systems theory, including stable and unstable manifolds,
as well as generic properties of vector fields, is used to develop a
theoretical characterization of the behavior near the region of attraction
boundary of a stable equilibrium point.
This theoretical foundation motivates the development of numerical algorithms
for assessing nonlinear stability in the presence of large disturbances, and
helps prove theoretical guarantees for these algorithms.

Relevant references:
1. M. W. Fisher and I. A. Hiskens. Hausdorff
Continuity of Region of Attraction Boundary Under Parameter Variation
with Application to Disturbance Recovery. *SIAM Journal of Applied
Dynamical Systems*, 21(1): 327-365, 2022.
2. M. W. Fisher and
I. A. Hiskens. Numerical Computation of Critical System Recovery
Parameter Values by Trajectory Sensitivity Maximization. In *IEEE
Conference on Decision and Control*, p. 8000-8006, 2019.
3. M. W. Fisher and I. A. Hiskens. Comments on “Stability Regions of
Nonlinear Autonomous Dynamical Systems.” *IEEE Transactions on
Automatic Control*, 66(12): 6194-6196, 2021.  4.

## Linear Control to Improve Nonlinear Robustness

<p align="center">
<img src="/figs/stability_2.png" width="400" height="386">`
</p>

One measure of nonlinear robustness is the margin for safe operation:
the smallest change in operating conditions - including system state and
parameter values - that would lead to a failure to recover from a given
nonlinear disturbance.
This project involves designing local linear feedback controllers in order to
increase the margin for safe operation by moving the system further away from
nonlinear instability.
To accomplish this, techniques are developed which vary parameter values so
as to increase the size of the region of attraction of a stable equilibrium
point in the directions of the most dangerous nonlinear disturbances.
Tools from modern dynamical systems theory are used to prove theoretical
guarantees for the algorithms.

Relevant references:
1. M. W. Fisher and I. A. Hiskens. Parametric
Dependence of Large Disturbance Response for Vector Fields with
Event-Selected Discontinuities. In *European Control Conference*,
p. 166-173, 2019.
2. M. W. Fisher and I. A. Hiskens. Numerical
Computation of Critical Parameter Values for Fault Recovery in Power
Systems. In *Power Systems Computation Conference*, p. 1-6, 2018.
3. M. W. Fisher and I. A. Hiskens. Parametric Dependence of Large
Disturbance Response and Relationship to Stability Boundary. In *IEEE
Conference on Decision and Control*, p. 1821-1827, 2017.


