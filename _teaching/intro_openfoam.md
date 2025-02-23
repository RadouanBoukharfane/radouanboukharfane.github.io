---
title: "Introduction to CFD using OpenFOAM"
collection: teaching
type: "Licence Sciences des Données"
permalink: /teaching/intro_openfoam
venue: "Université Mohammed VI Polytechnique"
date: 2021-09-01
location: "UM6P, Benguerir, Morocco"
---

OpenFOAM is a widely used open-source software package for Computational Fluid Dynamics (CFD). It has a large user base across various engineering and scientific fields, spanning both commercial and academic organizations. OpenFOAM offers an extensive range of features to solve complex fluid flow problems, including those involving chemical reactions, turbulence, and heat transfer, as well as applications in acoustics, solid mechanics, and electromagnetics. It is a free-to-use numerical simulation software, including support for HPC systems. In this course, you will learn how to simulate various flow configurations using the Computational Fluid Dynamics software OpenFOAM. This includes the simulation of laminar and turbulent flows, both steady-state and transient. Additionally, you will explore multiphase flow simulations. The course will cover how to select appropriate initial and boundary conditions for calculations. Furthermore, you will learn how to define a spatial domain and generate a mesh using either structured or unstructured grids. You will also learn how to edit runtime controls, run simulations, check solution convergence, and visualize results graphically with ParaView.

### Course Prerequisites

- Students should have basic computer management skills and be comfortable working with the Unix/Linux command line.

### Topics to Be Covered 

- General overview of OpenFOAM
- Lid-driven cavity example walkthrough
  * Pre-processing OpenFOAM cases
  * Configuring an OpenFOAM case
  * Running an OpenFOAM case
  * Post-processing OpenFOAM cases
- Stress analysis of the plateHole example
- Creating a custom solver
  * Adding a transport equation to `icoFoam`

### Learning Outcomes

By the end of the course, you will:

- Learn how to download, install, compile, and run standard OpenFOAM solvers and utilities.
- Learn how to develop and implement solvers and utilities.
- Learn how to implement a turbulence model.
- Learn how to define and implement custom boundary conditions.
- Gain basic knowledge of C++ and object-oriented programming.
- Learn how to use OpenFOAM in combination with Python, Gnuplot, ParaView, and other tools.
- Develop foundational skills in Linux (see link on homepage), Doxygen, compilation procedures, debugging, version control systems, and VTK.
- Apply your OpenFOAM knowledge through hands-on project work.
