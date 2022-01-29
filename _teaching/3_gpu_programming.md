---
title: "Introduction to GPU Programming"
collection: teaching
type: "Master Modélisation et Sciences des Données"
permalink: /teaching/gpu_programming
venue: "Université Mohammed VI Polytechnique"
date: 2021-09-01
location: "Benguerir, Morocco"
---


The Graphics Processing Unit or GPU is nowadays a mainstream component in Scientific Computing. For relatively little money one can have supercomputer performance. However, some extra work has to be done to make an ordinary sequential program suitable for use on the GPU.
One of the most important tools for using GPUs is currently "CUDA" (Compute Unified Device Architecture). This is basically an extension to the C programming language, which can be used to program the GPU in an easy way. 
During this course you will learn the basic principles of GPU programming and let you practise with many examples. After this course you should be able to make simple CUDA programs which can be run on a GPU.

### Course contents

The course focuses on three main topics:

-	GPU architecture. The computing and memory systems of different commercial GPUs are introduced. A comparison with conventional CPU and presentation of new upcoming GPUs will be given.

-	GPU programming with CUDA. The CUDA concepts and how to use them to develop applications for GPU are introduced by making examples from different fields, such as image processing or scientific computing. Also development tools, such debuggers and performance monitoring tools are presented.

-	GPU programming with GPU libraries and frameworks. High-productivity computing frameworks, among which OpenACC, will be presented. 

Students will be given access to the GPU cluster, Tegner, at PDC if they do not have access to a computer with GPU.

This short course is part of the program FIP (no idea what it stands for) proposed by *Arts et Métiers Institute of Technology*.

### Prerequisite
 
-	We are going to use the C/C++ language. Since programing GPU with CUDA is basically an extension of the C language, it is important that you refresh your C knowledge before starting the CUDA module of the course.

-	There are many online tutorials about C. Make sure that you know how to compile a C code from the command line, _i.e._, GCC, and write simple programs in C.

### Recommended reading

-	[CUDA for Engineers](https://www.amazon.fr/CUDA-Engineers-Introduction-High-Performance-Computing/dp/013417741X) by Duane Storti and Mete Yurtoglu.

-	[Programming Massively Parallel Processors](https://www.sciencedirect.com/book/9780128119860/programming-massively-parallel-processors) by David Kirk and Wen-mei W. Hwu.

