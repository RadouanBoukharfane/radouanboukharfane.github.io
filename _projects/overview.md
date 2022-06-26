---
title: "MSDA Group for computational physics and fluid mechanics"
excerpt: " 
The MSDA Group at MSDA/UM6P is a research group focuses on development and application of tools to perform scale-resolving simulations of transient flow phenomena and turbulence. In particular, we focus on development of novel high-order discretisations for use on structured and unstructured grids, as well as their implementation for massively-parallel many-core architectures. We are also interested development of novel meshing methods.
"
collection: projects
---


The MSDA Group for computational physics and fluid mechanics at MSDA/UM6P is a research group that includes two professors, graduate students and undergraduate students who undergo a wide range of studies and simulations related to computational fluid dynamics. Working with both development and applied numerical studies, the group is gaining a great expertise and knowledge in the CFD domain, which is currently the widest as well as the most efficient fluid flow testing tool. 


Now CFD is considered the number one tool among all fluid testing units due to the availability of high tech computers besides commercial and open-source CFD packages and libraries accessible to almost every one.

Our mission at the MSDA Group for computational physics and fluid mechanics at MSDA/UM6P is to help develop the science of CFD by devising new mathematical methodologies that render more robust CFD simulations. We also aim at conducting CFD analysis for different domains such as air-conditioing, oil and gas, aerodynamics, blood flow in arteries, heat transfer issues .. etc.

For the moment, our research interests are related to the design and implementation of novel numerical methods for hyperbolic and mixed hyperbolic/parabolic partial differential equations, as well as their application to solve realistic flow problems in various areas of natural science and engineering.

<hr style="border:3px solid black">

## Advising and Mentoring

- PhD students
---

	*	2022-present: Marwane Elkarii (CFD Simulation and Investigation of Slurry Flows in Pipelines)
	*	2022-present: Fatima Ez-Zahra El Hamra (Numerical Simulation of Non-Newtonian Fluid Flow with OpenModelica)

<hr style="border:3px solid black">

## Overview

<p align="justify">
All of our research projects fall in the category of computational science, which is the multi-disciplinary mix of applied math and numerical methods, programming for massively parallel supercomputing, and the physics of turbulence and fluid mechanics. 

Our overall vision is to bring high-fidelity turbulence simulations to the point where they can be routinely applied to real problems in engineering practice. This vision informs all of our work. In some projects we use supercomputing resources to learn more about turbulence physics, and we then try to take that knowledge to build new theoretical models that can be used to make predictions, build lower-cost models, and in general encode our understanding. In other projects we directly develop new algorithms or mathematical models, and then always with a mindfulness of how they would be used in practice.
</p>

<hr style="border:3px solid black">

## Current interests
---
*	Physics of supersonic turbulence & multiphase flows
---
*	Droplet turbulence interaction
---
*   Compressible Reacting Flows
---
The main difficulties in the simulation of compressible reactive flows arise when the chemical reactions introduce time scales that are significantly shorter than the hydrodynamic time scales. Standard shock capturing algorithms smear out the front so that a few grid cells lie within the shock profile. The numerically smeared out temperature profile contains values that are artificially raised above the ignition temperature with the potential to trigger the chemical reaction too early. When the reaction is fast, the gas can be completely burnt in the next time step shifting the discontinuity to the adjacent cell boundary leading to a nonphysical one-grid-cell per time step spurious wave. We have designed a new, fully conservative version of the ghost fluid method applicable for tracking material interfaces, inert shocks, and both deflagration and detonation waves in as many as three spatial dimensions. The exact discrete conservation properties are most important when tracking inert shocks and detonation waves, so that is the focus of this paper. In particular, we address the inviscid reactive Euler equations in the context of stiff detonation waves on coarse grids. The main difficulty here arises when the time scales of the chemical reaction are significantly shorter than the time scales of the fluid dynamics leading to a stiff source term and nonphysical wave phenomena. We use the level set method to track the location of the detonation wave and the ghost fluid method to treat the discontinuous quantities across the inert shock portion of that wave. This leads to a sharp non-smeared shock profile alleviating the nonphysical wave phenomena.
---
*	Shock/Turbulence interaction
---
*	Immersed Boundary Method
---
The prediction of fluid motion around structures is crucial in many important applications in science and engineering. Examples include the classical study of the aerodynamics of aircrafts or the hydrodynamics of ships, but also more modern applications such as the fluid dynamics occurring during materials processing such as the solidification of liquid metal alloys, the study of artificial swimmers or biological flows. For flow regimes where the Reynolds number is low, simulations focus on incompressible flows. This projet aims at developping Immersed Boundary Method Schemes for single phase flows.
---
*	Multi-scale and Multi-physics simulations
---
*	Direct Numerical Simulation of turbulent combustion
---
*	High Performance Computing
---