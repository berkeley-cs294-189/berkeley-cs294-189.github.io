---
layout: project
title: Assertion-Based Verification Lab - EECS151
nav_exclude: false
# Keep to ~2 sentences
description: Lab that teaches students fundamentals of assertion-based verification. Students write SystemVerilog assertions to verify the functionality of a FIFO buffer.
class_type: Introduction to Digital Design and Integrated Circuits
authors:
    - name: Anish Dhanashekar
      email: aeroanish@berkeley.edu
    - name: Kanav Mittal
      email: kanavmittal@berkeley.edu
# Suggested Sources (use as necessary)
presentations:
    - type: slides
      url: https://docs.google.com/presentation/d/1vobFQEKLYs1jiiQnYO9JhdP57POmnz8edgivLyZaygI/edit?usp=sharing
project_source:
    - type: github
      url: https://github.com/kanavmittal314/verification-lab-berkeley
    - type: website
      url: https://kanavmittal314.github.io/verification-lab-berkeley
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

## Instructor guides

SVA content references:
 - SystemVerilog Assertions Basics Website: [https://www.systemverilog.io/verification/sva-basics/](https://www.systemverilog.io/verification/sva-basics/)
 - SystemVerilog Assertions Apple Guest Lecture (may be guarded behind berkeley.edu login): [https://inst.eecs.berkeley.edu/~eecs151/fa25/static/lectures/lec18.pdf](https://inst.eecs.berkeley.edu/~eecs151/fa25/static/lectures/lec18.pdf)

You can find our [instructor guide](https://docs.google.com/document/d/10dDKbpFEE4OG_W9Gz2uIZHeFTQzw5QupWXlvYeQB7xw/edit?usp=sharing) with grading, solutions, and more advice for running the lab! This guide is private, but you can email us to get access.

## Requirements

- Enough TAs to conduct check-offs with students
- Students need to be in pairs
- [EDA Playground access](https://edaplayground.com/)
