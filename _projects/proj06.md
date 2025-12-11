---
layout: project
title: Embodied AI Lab - EECS 106B
nav_exclude: false
# Keep to ~2 sentences
description: Will AI robots take over the world? Who knows! ¯\(ツ)/¯ Let's drop the dramatic fiction and see what's **actually driving these machines**.
class_type: Robotic Manipulation and Interaction
authors:
    - name: Cassie Jeng
      email: cassie.jeng@berkeley.edu
      url: https://cjeng8771.github.io/cassiejeng/
    - name: Abigail O'Neill
      email: abbyoneill@berkeley.edu
      url: https://abbykoneill.github.io/
# Project Sources
presentations:
    - type: slides
      url: https://docs.google.com/presentation/d/1fcREXmnPPhnNSjTyJnlZHVHz49cWNx-DfS0yQKy_Aos/edit?usp=sharing
project_source:
    - type: github (part 1)
      url: https://github.com/abbykoneill/lerobot/tree/main/lab_part_1
    - type: github (part 2)
      url: https://github.com/abbykoneill/lerobot/tree/main/lab_part2
---

<!-- Leave this here. -->
1. TOC
{:toc}

## Introduction
The idea of AI robots developing their own brains and taking over the world is a dramatic storyline, not a reality. Our project cuts through this fear by giving students direct, **hands-on experience** with embodied AI, showing them exactly what is happening "under the hood." We demonstrate that the core technology is an evolution of classic engineering, linking traditional **controls and robot research** architectures to the new AI landscape. Students start with fundamental techniques like **teleoperation** (remote control) and simple intelligence built on **nearest neighbor computation** - where the robot finds the closest match to the current situation in its memory to decide its next move. This forms the essential base for understanding how modern robots achieve intelligent behavior without needing independent consciousness.

Moving beyond the basics, we integrate powerful new tools like **Vision-Language Models (VLMs)**, which let the robot understand the world by connecting what it sees with language (e.g., locating an object based on a spoken command). The VLM's output then drives the action through **Vision-Language-Action (VLA) models**. A key focus is on ensuring **safety for the output of VLAs**. Since these systems can generate complex, novel robot actions, we emphasize building robust safety protocols and constraints.

## Learning Goals
1. Imitation learning - Develop an imitation learning abstracted mental model for a pick-and-place task.
2. VLMs - Understand the input and outputs for VLMs. Compare different VLM implementations.
3. VLAs - Apply VLM intuition to robot use case, introducing VLAs.
4. Safety - Relate GenAI concepts to traditional robotics. Demonstrate understanding of GenAI limitations.

## Student Assignment
This lab is separated into two parts! Two begin, navigate to [Part 1](https://github.com/abbykoneill/lerobot/tree/main/lab_part_1), read through the [README](https://github.com/abbykoneill/lerobot/blob/main/lab_part_1/README.md), and then walk through the provided Jupyter notebook. Then, continue to [Part 2](https://github.com/abbykoneill/lerobot/tree/main/lab_part2), read the second [README](https://github.com/abbykoneill/lerobot/blob/main/lab_part2/README.md), and walk through the provided Jupyter notebooks.

## Instructor Guides
The grading guidelines/rubric for the lab final checkoff questions is available [here](https://docs.google.com/document/d/1wk4uSNiVx93OYwVAG2cJE-vnNyLYNsqW8A3gais9wAQ/edit?usp=sharing) for course instructors/TAs.

## Requirements
* Software: Python/Jupyter Notebook
    * [Suggested]: Google Colab
* Classroom: synchronous lab time with TAs, lab partners (two students)
    * [Suggested]: Open collaborative space set up, at least 1 TA for 2/3 pairs of partners
