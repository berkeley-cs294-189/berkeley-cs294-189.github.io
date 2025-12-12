---
layout: project
title: Embodied AI Lab - EECS 106B
nav_exclude: false
# Keep to ~2 sentences
description: Will AI robots take over the world? Who knows! ¯\(ツ)/¯ Let's drop the dramatic fiction and see what's actually driving these machines 🤖.
class_type: Robotic Manipulation and Interaction
authors:
    - name: Cassie Jeng
      email: cassie.jeng@berkeley.edu
      url: 
    - name: Abigail O'Neill
      email: abbyoneill@berkeley.edu
      url: 
# Project Sources
presentations:
    - type: slides
      url: [Presentation Slides](https://docs.google.com/presentation/d/1fcREXmnPPhnNSjTyJnlZHVHz49cWNx-DfS0yQKy_Aos/edit?usp=sharing)
project_source:
    - type: github
      url: [Part 1](https://github.com/abbykoneill/lerobot/tree/main/lab_part_1)
    - type: github
      url: [Part 2](https://github.com/abbykoneill/lerobot/tree/main/lab_part2)
    - type: overview
      url: [Lab Materials](https://docs.google.com/document/d/1dMt9y0JQ6oghVBbaNZE0aO2xIc8LnGNKdIRH9gJe_-E/edit?usp=sharing)
    - type: final_checkoff_grading_guidelines
      url: [Course Staff Grading Guideslines ⚠️Access Required](https://docs.google.com/document/d/1wk4uSNiVx93OYwVAG2cJE-vnNyLYNsqW8A3gais9wAQ/edit?usp=sharing)
---

<!-- Leave this here. -->
1. TOC
{:toc}

## Introduction
The idea of AI robots developing their own brains and taking over the world is a dramatic storyline, not a reality. Our project cuts through this fear by giving students direct, **hands-on experience** with embodied AI, showing them exactly what is happening "under the hood." We demonstrate that the core technology is an evolution of classic engineering, linking traditional **controls and robot research** architectures to the new AI landscape. Students start with fundamental techniques like **teleoperation** (remote control) and simple intelligence built on **nearest neighbor computation** - where the robot finds the closest match to the current situation in its memory to decide its next move. This forms the essential base for understanding how modern robots achieve intelligent behavior without needing independent consciousness.

Moving beyond the basics, we integrate powerful new tools like **Vision-Language Models (VLMs)**, which let the robot understand the world by connecting what it sees with language (e.g., locating an object based on a spoken command). The VLM's output then drives the action through **Vision-Language-Action (VLA) models**. A key focus is on ensuring **safety for the output of VLAs**. Since these systems can generate complex, novel robot actions, we emphasize building robust safety protocols and constraints.

## EECS 106B Course Context
EECS 106B Robotic Manipulation and Interaction introduces students to advanced topics and research in robotics and intelligent machines, including kinematics & control, obstacle avoidance & computer vision, manipulation, active vision, and reinforcement learning. It is expected that students have previously taken EECS 106A Introduction to Robotics, have a strong programming background and knowledge of Python and MATLAB, and have some prior experience with coursework in feedback controls.

## Learning Goals
This lab aims to add an introduction to embodied AI to the existing research topics covered in EECS 106B. Through the lab, students will:
1. Develop an **imitation learning** abstracted mental model for a pick-and-place task.
2. Understand the input and outputs for **VLMs**. Compare different VLM implementations.
3. Apply VLM intuition to robot use case, introducing **VLAs**.
4. Relate GenAI concepts to traditional robotics. Demonstrate understanding of GenAI limitations and **safety**.

## Student Assignment
This lab is separated into two parts. To begin:
1. Navigate to [Part 1](https://github.com/abbykoneill/lerobot/tree/main/lab_part_1), read through the [README](https://github.com/abbykoneill/lerobot/blob/main/lab_part_1/README.md), and walk through the provided [Imitation Learning](https://github.com/abbykoneill/lerobot/blob/main/lab_part_1/1_imitation_learning.ipynb) Jupyter notebook.
2. Continue to [Part 2](https://github.com/abbykoneill/lerobot/tree/main/lab_part2), read the second [README](https://github.com/abbykoneill/lerobot/blob/main/lab_part2/README.md), and walk through the provided Jupyter notebooks, starting with the [Introduction to ChatGPT](https://github.com/abbykoneill/lerobot/blob/main/lab_part2/1_chatgpt.ipynb).
3. When you've explored all notebooks, complete the [Final Lab Checkoff](https://github.com/abbykoneill/lerobot/blob/main/lab_part2/checkoff.md) with a lab TA and your lab partner.

## Instructor Guides
⚠️Access required - The grading guidelines for the lab final checkoff is available [here](https://docs.google.com/document/d/1wk4uSNiVx93OYwVAG2cJE-vnNyLYNsqW8A3gais9wAQ/edit?usp=sharing) for course staff. Please make a copy of the document before implementing any customizations to the guidelines.

## Requirements
* Software requirements: Python/Jupyter Notebook
* [Suggested] software: Google Colab
* Classroom logistics: Synchronous lab time with TAs, lab partners (pairs of students), at least 1 TA for 2-3 pairs of students, open collaborative lab space
