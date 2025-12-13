---
layout: project
title: Introducing Multilayer Perceptron Networks Calculations - EECS 188
nav_exclude: false
# Keep to ~2 sentences
description: Introduction to the maths behind neural networks
class_type: Intro to Artificial Intelligence
authors:
    - name: Melissa Fabros
      email: contact-email-only-if-you-want
      url: https://x.com/me_develops
# Suggested Sources (use as necessary)
presentations:
    - type: slides
      url: https://docs.google.com/presentation/d/11pz5fsISE5MOZVW-RLXQ9SHMv0heJQwYJaBJ5K0YRMM/edit?usp=sharing
project_source:
    - type: github
      url:
    - type: website
      url: 
    - type: google_drive
      url: https://drive.google.com/drive/folders/135nsMLeoTTe5H89snUAvc9FjK6oRRU49?usp=sharing
    - type: overleaf
      url:
---

<!-- Leave this here. -->
1. TOC
{:toc}

<!--  TODO: Put generic metadata info in template. -->
<!-- Start with h2, the page already includes your title. -->

## Introduction
Increased complexity of CS topics for upper division classes may offer few opportunities for peer teaching as a way for demonstrating mastery of a topic. This assignment for an upper division class on Introduction to Artificial Intelligence (EECS 188) seeks to provide opportunities for peer teaching and creativity in a mathmatically technical class. The heart of the assignment is for peers to teach each other by making "cheat sheets" for each other for use in a quiz or a test. 

The implementation of the assignment centers on introducing a way of teaching neural networks using spreadsheets, which was developed by Tom Yeh, in addition to mathmatical notation. EECS 188 is currently taught in a lecture with weekly discussion format. The assignment was conceived as a discussion or lab activity, but it can also be used in larger classes. 

## Learning Objectives:
- Deepen math intuition on the process of nodes’ activation weights “learning” in multilayer perceptrons with hands on activity through a spreadsheet presentation, and online visualization
- Scaffold transition from single node perceptron to neural net with hidden layers, and single to multi-class prediction, and project #5 (creating and training a classifier on the MNIST dataset)
- Develop awareness of meta-learning strategies
- Communicate technical ideas to others, creating clear and concise documentation
- Decouple success from solution accuracy and provide teaching others as a demonstration of mastery
- Provide an opportunity for creative expression in a technical course


## Requirements
- [AI by Hand worksheets](https://drive.google.com/drive/folders/135nsMLeoTTe5H89snUAvc9FjK6oRRU49?usp=sharing)
- [Tensorflow playground](https://playground.tensorflow.org)
- CS 188 slides
- At least 1 teaching assistant


## Assignment scaffolding  

- introduction what a node or perceptron is in a deep learning mode and classification problems (Lecture 20 in CS 188)
- Instructor/TA training (youtube): [Walk through of calculating a single node to translate the formula expression to a spreadsheet presentation](https://www.youtube.com/watch?v=jwyNzw0aclA) (2min)
- optional training (youtube): [Walkthrough how to complete the entire MLP worksheet](https://www.youtube.com/watch?v=NMOn7fJN1QI) (4min)
- TA explanation: Doing some translation between the formulas on the CS188 slides and how the values would look in a matrix. - 
- Distribution of Neural net worksheets on paper or with google sheets.

## Implemention for EECS 188 context (estimated time to execute 3 - 4hrs):  
* Setup before discussion section:
1: TA prep before class would require reviewing this video of a single node example calculation (2min)
2: TA demonstrates and trains a neural network online using tensorflow playground https://playground.tensorflow.org (2 min setup)
3: Settings can be variable but initially could follow the worksheet architecture and settings
    * Activation: ReLU
    * Problem type: classification
    * 4 hidden layers: 4 nodes, 3 nodes, 4 nodes, 3 nodes
    * Initial Hyperparameters: 
        * Spiral dataset
        * Batch size: 10
        * Noise: 25%
        * Training-test set ration: 60%
        * Learning rate: .03
        * Regularization: none
        * Regularization rate: none


* During Discussion:
1. TA sets up and frames discussion / lab about perceptrons and MLP from lecture (2-5min)
2. TA demonstrates and trains a neural network online using tensorflow playground https://playground.tensorflow.org (10-15min)
3. The online visualization can be used as early as the training and testing slides in lecture 19
4. TA walks through a single node perceptron example using the spreadsheet representation during discussion (10-15min):
Single node slide diagram -> spreadsheet
5. Students are presented with a completed spreadsheet (or with a faded parsons version). Students working in pairs start to draft a “cheatsheet” or step by step explanations on how the activation weights are “learning” or being calculated step by step on the spreadsheet with the instructions that it will be a teaching guide to solve the neural net (20-30 min) problems for others. Can use an online version or paper version of the worksheet.

* Homework: 
1. finish or refine their own copy of the cheatsheet or explainer to the spreadsheet presentation of the MLP to bring to lecture or next discussion (60-120 min). 
2. Review slides 20-38 for lecture 20
3. Include explanations of nodes, weights, bias, relu, sigmoid in plain english as it pertains to the spreadsheet
4. Provide instructions to how calculate the probabilistic output for inputs x1 and x2 with  weights initialized to 0 for an initial training pass
5. Provide instructions on how to use the spreadsheet to update weight values for case of  misclassification 1 or misclassification 2 from the lecture slides
6. Any “Warning” notes about possible missteps or notes on how to double check their work or tip and tricks

* Formative assessment: A quiz during lecture would be to trade their explainer notes to another student calculate the activation weights of an MLP with hidden layers (45 min)
    * Failure to bring the cheatsheet fails the assignment 0 - points. 
    * The pairs can be identified and matched in an earlier lecture. Or students just pass their notes to the person next to them or entire rows shift left their notes. 
    * A blank copy of the MLP architecture spreadsheet would be distributed in lecture or a discussion section.
    * The spreadsheet values are changeable with formulas that automate the answer key, different versions of the MLP can be distributed
        * The spreadsheet could be empty or be a faded parsons exercise where some of the values are already completed 
    * Using the new-to-them explainer notes, Students will complete fill in the blank values for the MLP architecture, answer some short answer questions about what ReLu does and assess the helpfulness of the explainer notes.
    * Students reflect on their cheatsheet with respect to the one they received after the rubric scoring. 


## Assignment  
- [available as pdf](https://drive.google.com/file/d/1fc67fwj8otTz46u-7XBx_m4hNvXdL0aA/view?usp=drive_link)  
__Objective:__  
Create a visual, hand-written, letter-sized, one-page (double-sided) "Navigator" that guides a fellow student through the logic of manual neural network calculations.  Graph paper is the recommended medium.

Your guide should cover the vocabulary and step through the execution of simple Logic Gate (Single Perceptron) as well the workings of complex Classifier (Multi-Layer Perceptron) from input through output.

In the following class, a peer student will only have your guide as a “cheat sheet” to answer questions about or demonstrate the calculations of weights, bias, relu or sigmoid functions in a neural net. You should cover how the formal math notations can be translated into concrete math manipulations (The Tom Yeh’s “by hand” methods would be a good model). 

Flag possible “gotchas” or tricky parts that they might have a hard time with because you had a hard time with the concept or task.



__Grading:__ 
If the person using your guide gets an “A” on the stress test, you will also receive an “A” as their navigator. If the person using your guide doesn't get an “A”, you will receive a combination of your own points on the test and a peer assessed grade of your guide. 

The criteria that the navigation guide would be graded on include: Visual Clarity & Design, Communication, Conceptual Clarity, Comprehensiveness, Scaffolding of concepts, Meta-learning awareness



## Grading
The quiz is the test of the "navigation" guide. My current thinking is that the final grade of the exercise comes in 2 parts: a rubric score of the study guide and the score on the test. If the student following a guide achieves an 90% & above, both students get the 90%+ points. If the student following the guide scores below the 90% threshold, students could recieve a mix of the peer assessment of the navigation guide and the points achieved on the "stress test".

The goal is to demonstrate mastery at teaching perceptron and MLP networks if the students do well in writing the study guides grading should be should be easy. Parsing out grades lower than the instructor-set threshold could invite complexity. 

Currently for the purposes of this class, the stress test is completing a blank worksheet. A more complex or comprehensive "stress" test can be implemented as well. In this case of completing a blank spreadsheet, grading could be simplified by grading only the final output, if the student completes the worksheet with the correct Y1 and Y2 probabilities then the full points for the worksheet and the study guide are awarded. If the learner does not get the Y1 and Y2 outputs correct, every empty cell value is considered an available point. The total points from the worksheet would be combined their peer-graded rubric score. Three example blank worksheets and keys are available in [google drive](https://drive.google.com/drive/folders/135nsMLeoTTe5H89snUAvc9FjK6oRRU49?usp=sharing)

If you would like to customize the spreadsheet the link is: [MLP by hand spreadsheet](https://docs.google.com/spreadsheets/d/1CuM1_8cndkqPayXEtGqNS6LI9T2rAEqT0Av0LKjy2qw/edit?gid=1880038000#gid=1880038000)

A sample rubric for the cheat sheet is available with the assignment instructions. 

## Escaping the Learning Objectives
In addition to failing to compile a study guide, students may escape the learning objective by purposely sabotaging their peers with disingenuous or faulty guides. Those that don't complete a study guide cannot participate in the quiz or worksheet activity and will receive a zero for the study guide assignment and a zero for the "quiz" that tests the study guide.  The instructor or TA will need redistribute study guide pairings for those completing the quiz using the study guide. 

In the case of sabatage, the study guide will be assessed by their peer and the peer grade would include the utility and focus of the study guide. 


## References
- [A Multi-institutional Study of Peer Instruction in Introductory Computing](https://eprints.gla.ac.uk/135493/1/135493.pdf)
- [A Practical Review of Mastery Learning](https://pmc.ncbi.nlm.nih.gov/articles/PMC10159400/)
- [A Bloom’s Taxonomy Model in 3D](https://www.teachthought.com/critical-thinking-posts/blooms-taxonomy-model-3d/)
- SIGCSE Nifty Assignments - AI in Orbit: Intelligent Classification of Space Weather Events with Machine Learning
- [Applying the Science of Learning: Evidence-Based Principles for the Design of Multimedia Instruction](https://pubmed.ncbi.nlm.nih.gov/19014238/)

