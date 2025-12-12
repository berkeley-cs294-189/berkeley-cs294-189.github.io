---
layout: project
title: We Have Spotify at Home - CS 61A / DATA C88C
nav_exclude: false
description: In this project, students will create a full stack web application similar to Spotify's Daylist feature, a daily customized music playlist. In the process, they'll learn a breadth of modern, practical software engineering skills.
class_type: Intro Computer Science (CS1)
authors:
    - name: Abigail Brooks-Ramirez
      email: a.brooks@berkeley.edu
    - name: Rebecca Dang
      email: rdang@berkeley.edu
      url: https://phrdang.github.io
presentations:
    - type: slides
      url: https://docs.google.com/presentation/d/1vRfwFCQPNcqwgUklYpY7cupvxkh3ZbCmVxaSypDVeLQ/edit?usp=sharing
project_source:
    - type: github_public_starter
      url: https://github.com/abigailrb03/daylist-at-home-starter
    - type: google_drive
      url: https://drive.google.com/drive/folders/1d3JhFyjGt5JCn0-c4dcXqRt-z_IiVfuZ?usp=drive_link
    - type: github_private_materials
      url: https://github.com/abigailrb03/cs294-project
---

1. TOC
{:toc}

## Introduction

At UC Berkeley, the introductory computer science courses offered are
[CS 61A: Structure and Interpretation of Computer Programs](https://cs61a.org)
(for intended EECS/CS majors) and [DATA C88C: Computational Structures in Data Science](https://c88c.org)
(for intended DS majors). Both courses offer an introductory survey of programming fundamentals like
Python and SQL syntax, basic data structures, algorithmic thinking, and interpretation of programming languages
(CS 61A only). Both are large courses, with CS 61A serving 1000+ students and DATA C88C serving 500+ students
each semester, typically first-year undergraduates.

Currently the projects in these courses are all autograded, tell students exactly what they need to do,
and lean more toward the theoretical side of programming. The projects were also developed several years ago,
and since then the tech stacks and cultural zeitgeist have matured
([Ants vs. SomeBees](https://cs61a.org/proj/ants/), the OOP/Inheritance project for both courses, is a play-on-words of
[Plants vs. Zombies](https://en.wikipedia.org/wiki/Plants_vs._Zombies), but now students might not even be familiar with the game).
Therefore, this project aims to bridge the gap between classroom learning and real-world applications by
teaching students real world software engineering skills (software design and abstraction, reading documentation, databases,
web development, APIs, HTTP requests/responses, error handling, computer security, pseudorandom number generation,
integrating LLMs into an app, etc.) with [modern technologies](#requirements) (Python >= 3.11, uv, pytest, Ollama) while remaining culturally relevant.

## Learning Goals

- Integrate knowledge of abstraction and OOP to implement a full stack web application
- Design and implement a set of classes that represent entities in the song dataset
- Implement API endpoints using Flask, SQLite, and the classes above

## Student Assignment

From the "Github public starter" link above, all instructions are in `README.md`.

## Instructor Guides

Request access from the project authors to access the "Github private materials" link above.

The private GitHub includes:

- Project solutions (`src/project/` directory)
- Script to compile solutions into starter code `.zip` file (`src/compile_starter.py` and `Makefile`)
- Script to fetch fresh data from the [Spotify API](https://developer.spotify.com/documentation/web-api) (`src/spotify-data/` directory)
- [GitHub Actions](https://docs.github.com/en/actions) workflows to ensure code quality and tests pass (`.github/workflows/` directory)

## Requirements

- Technical software requirements
  - [Python >= 3.11.14](https://github.com/abigailrb03/daylist-at-home-starter/blob/main/.python-version)
  - [Dependencies listed in pyproject.toml](https://github.com/abigailrb03/daylist-at-home-starter/blob/main/pyproject.toml) (see [uv.lock](https://github.com/abigailrb03/daylist-at-home-starter/blob/main/uv.lock) for full lock file of dependencies)
  - [uv >= 0.9.13](https://docs.astral.sh/uv/)
  - macOS 14 Sonoma or later, Linux, or Windows 10 or later to install [Ollama desktop app](https://ollama.com/download)
- Classroom/logistical requirements
  - Many TAs to be able to grade the design document component (Task 1A)
  - [Suggested] [Gradescope](https://www.gradescope.com/) for manual [grading of design doc PDFs](https://guides.gradescope.com/hc/en-us/articles/22249389005709-Grading-submissions-with-rubrics) and for [autograding](https://gradescope-autograders.readthedocs.io/en/latest/)
