# AMD-Instinct-GPU-Training

This course will give a deep dive into the AMD Instinct™ GPU architecture and its ROCm™ ecosystem, including the tools to develop or port HPC or AI applications to AMD GPUs. Participants will be introduced to the HIP (Heterogeneous-computing Interface for Portability) programming language for AMD GPUs, other higher-level GPU programming models such as OpenMP, OpenACC, and performance portable programming models such as Kokkos.
In addition, there will be presentations on other important topics such as GPU-Aware MPI, and Affinity. The AMD tool suite, including the debugger, rocgdb, and the profiling tools rocprof, omnitrace, and omniperf will also be covered. A short introduction will be given into the AMD Machine Learning software stack including PyTorch and Tensorflow and how they have been used in HPC.



After this course, participants will

- have learned about the many GPU programming languages for AMD GPUs
- understand how to get performance scaling
- have gained knowledge about the AMD programming tools
- have gotten an introduction to the AMD Machine learning software
- know about profiling and debugging.


# Prerequisites and content levels

Prerequisites
Some knowledge in GPU and/or HPC programming. Participants should have an application developer's general knowledge of computer hardware, operating systems, and at least one HPC programming language.

See also the suggested prereading below (resources and public videos).







Course Curricula and Content Levels
------------------------------------

Before registering for a course, please review the information concerning Entry Level and Content Level that is indicated on the course information page. This will assist you in selecting a training activity that is appropriate for your knowledge level and professional needs.



-------------------------------
MPI: Message Passing Interface:
-------------------------------

- MPI Overview
- MPI Process Model (8.7-8)
- Point-to-Point Communication (3.1-6, 8.6)
- Non-Blocking Communication (3.7+10)
- Collective Communication (5.1-11+13)
- Error Handling (8.3-5)

  MPI Intermediate content:
  --------------------
    - Groups and communicators, Environment Management, MPI_Comm_split, intra- & inter-communicators (6.1-5)
    - Virtual Topologies (7.1-5, 3.11)
    - One-sided Communication (11, 8.2)
    - Derived Datatypes (4.1.1-5+9)
    - Parallel File I/O (basics) (13)
    - Parallel File I/O (fileviews) (13.3)
    - Parallel File I/O (access methods) (13)
    - Best Practice
    - The new Fortran module mpi_f08 (17.1)
    - Collective Communication, advanced topics, Nonblocking Collectives (5.12), MPI_IN_PLACE (5.2.1)
    - Re-numbering on a cluster, Collective communication on inter-communicators (6.6), Info object (9), Attribute caching & naming (6.7-8), Implementation 
      information (8.1)
    - Neighborhood Communication (7.6-7) and MPI_BOTTOM (4.1.5)
    - Shared Memory One-sided Communication (11.2.3)
    - Shared Memory synchronization rules (11.4-5)

  MPI Intermediate content:
  --------------------
    - Groups and communicators, Environment Management, MPI_Comm_split, intra- & inter-communicators (6.1-5)
    - Virtual Topologies (7.1-5, 3.11)
    - One-sided Communication (11, 8.2)
    - Derived Datatypes (4.1.1-5+9)
    - Parallel File I/O (basics) (13)
    - Parallel File I/O (fileviews) (13.3)
    - Parallel File I/O (access methods) (13)
    - Best Practice
    - The new Fortran module mpi_f08 (17.1)
    - Collective Communication, advanced topics, Nonblocking Collectives (5.12), MPI_IN_PLACE (5.2.1)
    - Re-numbering on a cluster, Collective communication on inter-communicators (6.6), Info object (9), Attribute caching & naming (6.7-8), Implementation 
      information (8.1)
    - Neighborhood Communication (7.6-7) and MPI_BOTTOM (4.1.5)
    - Shared Memory One-sided Communication (11.2.3)
    - Shared Memory synchronization rules (11.4-5)
  
  - Community-targeted and domain-specific content
    ----------------------------------------------
    - Derived Datatypes and Resizing (4.1.7-12, 4.2-3)
    - MPI and Threads (12.4)
    - Probe, Cancel, Persistent Requests (3.8-9)
    - Process Creation and Management (10)
    - Other MPI Features (1-2, 12.1-3, 14-16, 2.6.1, 17.2, 8)
    - MPI Parameter Tuning





-------------------------------------------
Shared memory parallelization with OpenMP:
-------------------------------------------
   - Overview and execution model (OpenMP 3.1 features)
   - Work sharing directives (OpenMP 3.1 features)
   - Data environment (OpenMP 3.1 features)

     Intermediate content:
     ---------------------
     - Heat Example (practical/homework)
     - Pitfalls

     Community-targeted and domain-specific content
     ----------------------------------------------
     - OpenMP-4.0 and 4.5 Extensions (OpenMP 4.0 and 4.1 features, without GPU support)



-------------------------------------
Iterative solvers and parallelization
--------------------------------------

- Parallelization of Explicit and Implicit Solvers
- Numerical and parallel libraries

   - Advanced Content:
     ----------------
     Parallel Programming Models on Hybrid Systems / MPI + OpenMP

  -  Community-targeted and domain-specific content
     ----------------------------------------------
     
      - Particle-based domain decomposition
      - PETSc, An Introduction
      - Laplace-Example with MPI and PETSc: Introduction
      - Laplace-Example with MPI and PETSc: Writing a parallel MPI program with a CG solver
      - Laplace-Example with MPI and PETSc: Laplace-Example with PETSc
      - Iterative Linear Solvers




--------------------------------------
Visualization
--------------------------------------
 - Introduction to concepts of visualization
 - Introduction to the use of graphic tools

   - Intermediate content
     --------------------
     - Extension of graphic tools with own programming steps
     - Coupling of simulations with real-time visualization
     - Visualization of parallel applications

   - Advanced content
     ----------------
     - Advanced themes
      




--------------------------------------
GPU programming
---------------------------------------

- Intermediate content
   ---------------------
  - Introductory, CUDA, OpenACC, OpenMP GPU directives

- Advanced content
  -----------------
  - Programming of Clusters of GPUs
 

------------------------
C++ programming language
------------------------
- Introduction

  Intermediate content:
  ---------------------
  - Intermediate C++: Look for the courses "Modern C++ Software Design (Intermediate)"

  Advanced content:
  ----------------
  - Advanced C++: Look for the courses "Modern C++ Software Design (Advanced)"
  - C++ and HPC performance programming
  - C++14 shared memory programming








------------
Resources
------------

 - Book on HIP programming - Porting CUDA
   ---------------------------------------
     - Accelerated Computing with HIP,  Yifan Sun, Trinayan Baruah, David R Kaeli, ISBN-13 ‏ : ‎ 979-8218107444
       
- ENCCS resourses
  ---------------
    - Developing Applications with the AMD ROCm
      
- LAB-NOTE series on GPUOpen.com:
  ------------------------------
    - Finite difference method - Laplacian part 1
    - Finite difference method - Laplacian part 2
    - AMD matrix cores
    - Introduction to profiling tools for AMD hardware
    - AMD ROCm™ installation
    - AMD Instinct™ MI200 GPU memory space overview 

- Quick start guides at Oak Ridge National Laboratory
  ---------------------------------------------------
  - Crusher quick-start guide
  - Frontier user guide



---------------
Agenda
----------------

 - Day 1:
   ------

     - HLRS Intro
     - AMD Presentation Roadmap
     - Introduction to the System for Exercises
     - Introduction to the AMD Architecture, including FPGA
     - Overview of ROCm and Compilers, Infinity Hub/HPC Community
     - Introduction to HIP
     - HIP Exercises
     - Porting applications to HIP
     - Porting exercises


 - Day 2 - Additional GPU Programming Languages:
   --------------------------------------------
   
    - Introduction to OpenMP
    - OpenMP® Exercises
    - Advanced OpenMP® and Mixing HIP and OpenMP®
    - Performance Portability Frameworks; Intro to Kokkos
    - Kokkos Exercises
 

- Day 3 - AMD Performance Considerations and Debugging
  ----------------------------------------------------

   - AMD Communication Fabrics and GPU-Aware MPI
   - GPU-Aware Exercises
   - AMD Node Memory Model
   - Memory Model Exercises
   - Affinity - Placement, Ordering and Binding
   - Affinity Exercises
   - Debuggers - rocgdb
   - Rocgdb exercises


Day 4 - AMD Profilers and Machine Learning
-----------------------------------------

  - Introduction to rocprof
  - Rocprof Exercises
  - Introduction to Omnitrace
  - Omnitrace Exercises
  - Introduction to Omniperf
  - Omniperf Exercises
  - Machine Learning in HPC; Introduction to ML on AMD
  - Examples of Machine Learning projects
