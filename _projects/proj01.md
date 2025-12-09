---
layout: project
title: Assertion-Based Verification Lab - EECS151
nav_exclude: false
# Keep to ~2 sentences
description: Introduction to Digital Design and Integrated Circuits
class_type: Intro Computer Science
authors:
    - name: Anish Dhanashekar
      email: aeroanish@berkeley.edu
    - name: Kanav Mittal
      email: kanavmittal@berkeley.edu
# Suggested Sources (use as necessary)
presentations:
    - type: slides
      url:
project_source:
    - type: github
      url:
    - type: website
      url: https://inst.eecs.berkeley.edu/~cs61a/fa24/projects/proj01/
    - type: google_drive
      url:
    - type: overleaf
      url:
---

<!-- Leave this here. -->
1. TOC
{:toc}

<!--  TODO: Put generic metadata info in template. -->
<!-- Start with h2, the page already includes your title. -->

## Introduction

There is a noticeably growing interest in verification from both academia and industry, driven by the goal of producing bug-free chips. Assertion-Based Verification (ABV), in particular, is an increasingly important step in hardware design. We hope this lab assignment on ABV will prepare students for research or industry careers in hardware verification.

In this lab assignment, students will write SystemVerilog Assertions (SVA) to verify the behavior of Finite State Machines (FSMs), which is how every hardware design is represented pictorially. This lab will help students grow their ABV knowledge and develop skills like FSM comprehension and assertion writing. In the context of UC Berkeley's EECS151, this lab will occur prior to the final project, as equipping students with the ability to verify their designs during the implementation process will help avoid long, intractable debugging in their projects later during the semester. We expect the lab assignment to take students 3 hours to complete (excluding a 1-hour pre-lab).

## Learning Goals 

- Understand why assertion-based verification is important for hardware design.
- Identify 1:1 mappings of components of a specification to assertions that can be written.
- Write a comprehensive set of SystemVerilog Assertions (SVA) that follow good stylistic practices.
- Run SVA written against provided implementations of the FSM design in SystemVerilog.
- Evaluate the completeness/coverage and correctness/syntax of assertions and areas for improvement.

## Student assignment

[Lab website](https://kanavmittal314.github.io/verification-lab-berkeley/)

## Requirements
