---
layout: project
title: Debugging Labs - Data 8
nav_exclude: false
# Keep to ~2 sentences
description: Two labs focused on teaching students how to effectively debug code, including step-by-step guides, best practices, and practice problems on debugging.
class_type: Foundation of Data Science
authors:
    - name: Apollo Loh
      email: apollo.loh@berkeley.edu
    - name: Brandon Su
      email: brandonsu@berkeley.edu
# Suggested Sources (use as necessary)
presentations:
    - type: slides
      url: https://docs.google.com/presentation/d/1Tbq3UFu_4oD0wEb9_l5Oa-mNq9ndooc0zmA7QB8Q7kQ/edit?slide=id.g3adc3b7bf93_0_2458#slide=id.g3adc3b7bf93_0_2458
project_source:
    - type: google_drive
      url: https://drive.google.com/drive/folders/11KygnlLV4wijn1Llpx7RmgY1wPyJO0x0?usp=sharing
---

<!-- Leave this here. -->
1. TOC
{:toc}

<!--  TODO: Put generic metadata info in template. -->
<!-- Start with h2, the page already includes your title. -->

## Introduction
This lab is designed to strengthen students’ debugging skills by having them work with code that intentionally contains multiple errors. Students will be provided with example inputs, outputs, and starter code, but quickly discover that the program fails or produces incorrect results. Through guided questions, they will identify where errors occur, interpret error messages, explain the underlying issues, and propose fixes before modifying the code. In some cases, correcting one bug may reveal additional logic or output issues, reinforcing the iterative nature of debugging. We designed this lab because many students struggle to read and diagnose error messages, even when the messages appear straightforward. By practicing systematic debugging, students will develop a foundational skill essential for all future programming work.

## Course Context
Lab A will be introduced when students first gain explore table methods and functions, which is around week 4 of the semester. Once they get more familiarity with table methods and start creating visualizations, they will then be introduced to Lab B, around week 6 of the semester.

## Learning Goals
- **Explain expected inputs and outputs** of table/array methods and operations
- **Describe the different types of errors** they might encounter when working on a data science project and why they are important.
  - **Programming errors**: TypeError, TimeoutError, etc
  - **Data analysis errors**: Wrong order of operations (e.g. aggregating then filtering)
- **Perform a root cause analysis of an error** to understand where and why it is occurring.
- **Assess the effectiveness of a generated visualization** and whether or not it supports or detracts from the intended purpose

## Student Assignment
- In the Google Drive folder, `Lab A` and `Lab B` contain their respective `.ipynb` files along with any additional assets needed for each lab.

## Instructor Guides
- Similar to other Data 8 labs, students should work on the assignments during the second hour of the Data 8 lab section. While students work on the assignment, staff members should walk around assisting students and checking that students are answering the free response questions correctly.

## Requirements
- Standard Data 8 libraries (`numpy`, `datascience`, `otter-grader`, etc.)
- We recommend having 2-3 staff members present during lab sections since these labs have more manually graded FRQs compared to other labs. We encourage students to have open dialogues and conversations with their peers and the staff to better understand how to debug effectively.
