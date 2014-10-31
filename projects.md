---
layout: page
title: Projects
permalink: /projects/
---

## Ongoing

#### Lazy Cloud Init
Collection of shell scripts for quickly configuring new virtual machines running a variety of operating systems and Linux distributions. The main goals are to minimize dependencies and initial overhead. LCI currently only requires Bash and cURL and is run with a single command. Available on [GitHub](https://github.com/andrewseidl/lazy-cloud-init).

#### Raft.bf
Challenge: attempt to implement the [Raft consensus algorithm](https://raftconsensus.github.io/) in [Brainfuck](http://www.muppetlabs.com/~breadbox/bf/). In order to maintain some sanity, certain helper functions such as network communication, timers, and PRNGs are instead implemented in Python. Code and design documents on [GitHub](https://github.com/andrewseidl/raft.bf), blog post forthcoming.

## Maintenance Only

#### ParallelUtils.cmake
Written to support student projects in ME 964: High Performance Computing for Applications in Engineering. ParallelUtils.cmake provides a set of macros to ease the configuration of CMake-based C++ projects utilizing [CUDA](https://www.nvidia.com/cuda), [MPI](http://www.mcs.anl.gov/mpi/), and [OpenMP](http://openmp.org/). Available on [GitHub](https://github.com/andrewseidl/ParallelUtils-cmake).


## Retired

#### PhysBAM-CMake
Written in conjunction with CS 838: Advanced Modeling and Simulation. This provides a [CMake](http://www.cmake.org)-based build system for [PhysBAM](http://physbam.stanford.edu/), a multiphysics simulation library from Stanford. Development has been resumed by [Hammad Mazhar](http://hamelot.co.uk) and is available on [GitHub](https://github.com/hmazhar/physbam_public).

#### MC-Awesome
Final project for NE 408: Ionizing Radiation. MC-Awesome was a parallel framework for simulating particle transport through media via Monte Carlo methods, similar to [MCNP](https://mcnp.lanl.gov/). The code utilized the [Thrust](http://thrust.github.io/) library, allowing computations to be performed on both CPUs and CUDA-based GPUs. The final simulation utilized 1024 CPU cores and 2 TB of RAM.
