---
layout: project
title: CS61Cuda - CS61C
nav_exclude: false
# Keep to ~2 sentences
description: Welcome to CS61Cuda!! This is a mini‑project that introduces you to GPU programming with CUDA by building up to a fast matrix multiply. You’ll start with a CPU reference, write your first CUDA kernels, learn to reason about grids/blocks/threads, and finally add simple vectorization (SIMD) on the GPU. An optional performance sandbox lets you explore optimizations for bragging rights.

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

- Reason Down The Stack: understand the relationships between layers of abstraction 

- Become Hardware Aware: develop understanding of architecture and its impacts 

- Optimize: use full-stack awareness to design and optimize programs  

- Reinforce Parallelism: synthesize the different types of parallelism learned across previous labs/lectures  

- Matrix Proficiency: build understanding of indexing, bound checks, memory access patterns, and kernel design

- Hands-on Programming: get practice designing optimized programs on   modern GPU architectures

- Memory vs Compute: gain intuition of where programs tend to become memory vs compute bound

## Requirements
