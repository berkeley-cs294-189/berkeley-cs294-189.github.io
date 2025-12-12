---
layout: project
title: Spam & Ham Projects, Extended - Data 100
nav_exclude: false
# Keep to ~2 sentences
description: This project series has students build a binary classifier that can distinguish spam (junk, commerical, or bulk) emails from ham (regular non-spam) emails. This extended version emphasizes the planning and delivery stages of the data science lifecycle.
class_type: Principles and Techniques of Data Science
authors:
    - name: James Geronimo
      email: jegeronimo@berkeley.edu
      url: https://jegeronimo.com/
    - name: Brandon Concepcion
      email: brandon_concepcion@berkeley.edu
      url: https://brandonconcepcion.com/
# Suggested Sources (use as necessary)
presentations:
    - type: slides
      url: https://docs.google.com/presentation/d/1VUAtGDQjdyteAUpwGDWDbJhZR5We12t4FwonkA7JFM4/edit?usp=sharing
project_source:
    - type: github
      url: https://github.com/jegeronimo/cs294-189
    - type: google_drive
      url: https://drive.google.com/drive/folders/1e_nr7HPBZMsMUK9xQIoZ3V4fCKz13I_6?usp=sharing
---

<!-- Leave this here. -->
1. TOC
{:toc}

<!--  TODO: Put generic metadata info in template. -->
<!-- Start with h2, the page already includes your title. -->

## Introduction

In the existing Project B1 and B2, the overarching goal is for students to create a binary classifier that can distinguish spam (junk, commercial, or bulk) emails from ham (regular non-spam) emails. In order to better enable students to start their careers as data scientists, we propose an extended project that provides exposure to the planning, ideation, and delivery stages of data science projects.

In Project B0, students are tasked with building a design document that demonstrates their high-level understanding of the data (e.g., data processing, feature engineering). In Project B1, students will create a simple binary classifier that can distinguish spam emails from ham emails. Here, they will feature engineer text data, use the `sklearn` library to process data and fit models, validate the performance of the model, and minimize overfitting. Building off of the design document in Project B0, this focuses on initial analysis, feature engineering, and logistic regression.

## Learning Goals
For Project B0:
- Formulate a clear data science question
- Understand/describe the dataset
- Plan data processing and representation
- Explore the available data
- Develop/justify feature engineering

For Project B1:
- Incorporate B0 findings to aide analysis
- Feature engineer with text data
- Use sklearn to process data and fit models
- Validate model performance and minimize overfitting

## Student Assignment
From the [GitHub](https://github.com/jegeronimo/cs294-189), the supplementary materials for Project B0 and Project B1 can be found in the `README.md` file. The relevant links are pasted below for convenience:
- [Project B0 Instructions](https://datahub.berkeley.edu/hub/user-redirect/lab/tree/cs294-189/projB0.pdf)
- [Project B0 Notebook](https://datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fjegeronimo%2Fcs294-189&branch=main&urlpath=lab%2Ftree%2Fcs294-189%2FprojB0.ipynb)
- [Project B1 Notebook](https://datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fjegeronimo%2Fcs294-189&branch=main&urlpath=lab%2Ftree%2Fcs294-189%2FprojB1.ipynb)

## Instructor Guides
From the [Google Drive], the supplementary solutions can be found, but are only available upon request.

## Requirements
- Standard Data 100 libraries (e.g., `pandas`, `numpy`, `otter-grader`, `sklearn`)
- This is a partner project, so students should be able to choose or be assigned pairs, ideally through their discussion sections.
- [Suggested] [Pensieve](https://www.pensieve.co/) for AI-grading written components and autograding coding components.
