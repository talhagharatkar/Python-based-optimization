# Project Overview
This repository is a practical, code-first introduction to optimization techniques commonly used in Operations Research and management science. It serves as a companion to the textbook "An Introduction to Management Science: Quantitative Approaches to Decision Making" by Anderson, Sweeney, and Williams.

The primary goal is to provide clear, hands-on Python implementations of fundamental optimization models, making the concepts more accessible and applicable.

Key Features & Content
Core Optimization Techniques:

Linear Programming (LP): Solving resource allocation and profit maximization/minimization problems.

Integer Linear Programming (ILP): Addressing problems where solutions require integer values (e.g., yes/no decisions, whole units).

Transportation Problems: Optimizing the cost of shipping goods from multiple sources to multiple destinations.

Transshipment Problems: An extension of transportation models that includes intermediate nodes.

Assignment Problems: Optimally assigning tasks to agents (e.g., jobs to machines, workers to projects).

Technology Stack:

Language: Python

Key Library: PuLP - A popular linear programming modeler for Python that allows users to describe problems in a natural way and connect to various solvers (like CBC, GLPK).

Solvers: Uses open-source solvers bundled with PuLP (e.g., CBC).

Repository Structure:
The code is organized into Jupyter Notebooks (.ipynb files), each dedicated to a specific type of problem:

01_Linear_Programming.ipynb

02_Integer_Linear_Programming.ipynb

03_Transportation_Problem.ipynb

04_Transshipment_Problem.ipynb

05_Assignment_Problem.ipynb

Pedagogical Approach:
Each notebook typically follows a clear pattern:

Problem Definition: States a classic business or logistics problem.

Mathematical Formulation: Outlines the decision variables, objective function, and constraints.

Python/PuLP Implementation: Provides step-by-step code to build and solve the model.

Solution Interpretation: Prints and explains the optimal results (variable values, objective function value).

---

## Requirements

* Python 3+
* scipy (`pip install scipy`)
* numpy (`pip install numpy`)
* PuLP (`pip install pulp`)
* CVXPY (`pip install cvxpy`)

---
