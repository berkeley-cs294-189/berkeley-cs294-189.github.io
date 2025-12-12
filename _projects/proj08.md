---
layout: project
title: CS61Cuda - CS61C
nav_exclude: false
# Keep to ~2 sentences
description: Welcome to CS61Cuda!! This is a mini‑project that introduces students to GPU programming with CUDA by building up to a fast matrix multiply. They will start with a CPU reference, write CUDA kernels, learn to reason about grids/blocks/threads, and finally add simple vectorization (SIMD) on the GPU. An optional performance sandbox lets students explore optimizations for bragging rights.

class_type: Intro Computer Architecture
authors:
    - name: Malavikha Sudarshan
      email: malavikhasudarshan@berkeley.edu
      url: https://www.linkedin.com/in/malavikha-sudarshan/
    - name: Chloe Shen Yi Wong
      email: chloe.wong@berkeley.edu
      url:
# Suggested Sources (use as necessary)
presentations:
    - type: slides
      url: https://docs.google.com/presentation/d/1i2_tcdh2HcAU4fL4XUy5LmnYnvEv76FIPNrj7iZDMp4/edit?usp=sharing
project_source:
    - type: github
      url: https://github.com/malavikhasudarshan/cs61cuda
    - type: website
      url: https://malavikhasudarshan.github.io/cs61cuda/
---

<!-- Leave this here. -->
1. TOC
{:toc}

<!--  TODO: Put generic metadata info in template. -->
<!-- Start with h2, the page already includes your title. -->

## Introduction

CS61C is UC Berkeley's introductory student class to the hardware-software interface, and topics that span this boundary. It covers a survey of topics from C down to the datapath; a ‘survey’  down the stack unlocking further low-level UD classes.

**CS61Cuda** is the “The New Project 4/Lab 8”; it fills a crucial missing gap - a practical assignment involving combining parallelism concepts to optimize programs (and showcase creativity!) It is inspired by CS61C Spring 2014 (thank you Prof. Sagar K for providing your materials from that semester!) 

Previously, CS61C had a parallelism assignment - 61kaChow - with various issues. Both students and staff felt it did not actually help students with understanding of parallelism and was very hard to debug. Regardless, there was a need to give students practice…

The motivation for this new project that we developed was to move abstract lecture content to a tangible project. (and get NVIDIA funding :p), give students hands-on exposure to modern parallel programming models, reinforce course concepts and provide an introduction to kernel/GPU programming.

Logistically, we estimate that this project will slot in during approximately Week 12 of the semester, shortly after the five parallelism lectures. It is estimated to take 4-6 work hours and will probably be assigned with a due date of ~2 weeks later.

## Learning Goals

- Reason down the stack: understand the relationships between layers of abstraction 

- Become hardware-aware: develop understanding of architecture and its impacts 

- Optimize: use full-stack awareness to design and optimize programs on modern GPU architecture

- Reinforce parallelism: synthesize the different types of parallelism learned across previous labs/lectures  

- Matrix proficiency: build understanding of indexing, bound checks, memory access patterns, and kernel design

- Memory vs compute: gain intuition of where programs tend to become memory vs compute bound

## Student Assignment

The [Github](https://github.com/malavikhasudarshan/cs61cuda/tree/main) contains the source files, which students can clone from. 

Instructions and the CUDA primer can be viewed on the [assignment website](https://malavikhasudarshan.github.io/cs61cuda/)
or on the [Github README.md](https://github.com/malavikhasudarshan/cs61cuda/tree/main?tab=readme).

## Instructor Guides

Instructors can contact us via email for the Github repository containing staff solutions and a Gradescope autograder script.


Currently, we can provide the following to instructors: 
- Website: stored in a repository for easy updating + access
- Resources: code from other courses on parallel programming 
- Solutions: sample solutions for the guided portions of the class
- Autograder: includes Gradescope integration (JSON file results) for convenient porting
- Grading: quantitative breakdown of grading for the optimized section

## Requirements
**Technical requirements**
- CUDA‑capable GPUs on EECS Hive machines
- CUDA toolkit (e.g., cuda/12.x module with nvcc)
- C++17 compiler (via nvcc, g++)
- Make (make and provided Makefile)
- Git (clone starter repo, submit via Git/Gradescope)

**Classroom/logistical requirements** 
- Access to Hive GPU lab machines or remote SSH into Hive
- In‑person lab/OH time for debugging CUDA
- Enough TAs/tutors/academic interns to support debugging and manually grade free response written questions
