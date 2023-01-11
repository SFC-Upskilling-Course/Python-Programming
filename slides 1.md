---
title: SFC Upskilling Course  - Technology and Skills for Engineering the Future
description: Module Slides for the Python programming - introduction and preface
theme: uncovered
paginate: true
math: katex
transition: fade
_paginate: false
style: |
  .columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
  }
_backgroundColor: "#FFF"
_color: "#093867"

---

<!-- _header: ![h:5em](assets/UoG_keyline.svg) -->

# SFC Upskilling Course  - Technology and Skills for Engineering the Future

Introduction to Computer Programming

Hasan T Abbas
Lecturer, James Watt School of Engineering
[Hasan.Abbas@glasgow.ac.uk](mailto:Hasan.Abbas@glasgow.ac.uk)

<!-- transition: fade -->
<!-- <style scoped>a { color: #eee; }</style> -->

<!-- This is presenter's note. You can write down notes through HTML comments. -->

---

# What to Expect

In this module of the upskilling course, you will:

- get started with the basics of Python and C programming languages 
- learn the recipes and tricks for data science experiments
- fetch, analyse and visualise data
- communicate with connected devices using the C programming language

---

# Programming in Python

- Extensible programming language
- Well-suited for a variety of technical tasks
- Several off-the-shelf libraries to get going
- Artificial intelligence is mostly implemented using Python

---

# Python Preface

Python is an interpreted high-level programming language for a wide range of programming tasks.

- Interpreted — Python does not require 'compiling', you can run your script as soon as you've written it, and you can even run small snippets directly in a Python console.
- High-level — the code you write in Python is relatively human-readable and very different from the instructions received by the computer when your code runs.
- Programming — using a set of instructions for computers to create algorithms that complete a task, usually to make our lives more efficient.

---

# Brief History of Python

- Released in 1991
- Simplicity and readability are the two pillars of python philosophy
- Was not designed with any particular use case in mind
- The functionality can be extended by using modules and libraries

---

# So what is a Jupyter Notebook?

- A standalone computer file that contains the computer program, along with the necessary documentation, and most importantly results
- A web-based interactive environment with `cells` of information
- We can recognise a Jupyter notebook by the `.ipynb` file extension
- We will use 'Jupyter Hub', a multi-user server a Jupyter Notebook environment for completing the programming unit. We recommend the online version 'Jupyter Lite' which can be accessed at [https://jupyter.org/try](https://jupyter.org/try).

---


# How to get help

Python's documentation is the best place to seek technical help. Below are some commonly used modules that we will use in this module

- [NumPy](https://docs.scipy.org/doc/numpy/) — for numerical analysis
- [SciPy](https://docs.scipy.org/doc/scipy/reference/) — for scientific computation
- [Matplotlib](https://matplotlib.org/) — Plotting library for matrix data

---

# Example Python Code

The code block below computes the distance of the point described by $(x,y)$ co-ordinates $(4,5)$ from the origin using the formula $r = \sqrt{x^2 + y^2}$ and prints the result on the screen

```python

import numpy as np # import numpy library for numerical computation
x = 4 # store the values of 4 and 5 to variables x and y respectively
y = 5
r = np.sqrt(x**2 + y**2) # calculate the distance using the Pythogorean theorem
print(r) # Display the value of the variable r on screen

```