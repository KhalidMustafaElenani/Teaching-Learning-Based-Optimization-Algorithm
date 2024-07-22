# Teaching Learning-based Optimization (TLBO) Algorithm
![Swarm_intelligence](https://img.shields.io/badge/Swarm%20intelligence%20-%20brown?style=plastic)
![Teaching_Learning_based_Optimization](https://img.shields.io/badge/Teaching_Learning_based_Optimization-2011-%20teal?style=plastic)
![License](https://img.shields.io/badge/license%20-%20MIT%20-%20darkred?style=plastic)
![Python Version](https://img.shields.io/badge/Python-3-%20teal?style=plastic)
![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Open_Issues](https://img.shields.io/badge/Issues%20-%200%20-%20orange?style=plastic)

## Description
This repository contains a Python implementation of the Teaching Learning-based Optimization (TLBO) algorithm. TLBO is a stochastic population-based optimization method inspired by classroom learning dynamics. In TLBO, individuals in a population act as both teachers and learners, engaging in iterative knowledge transfer to evolve solutions.

The algorithm consists of two main phases:
1. **Teacher Phase**: Generates new solutions based on the best solution and the population mean, followed by a greedy selection process.
2. **Learner Phase**: Creates new solutions using a partner solution, followed by another greedy selection process.
This method is used for solving various optimization problems by leveraging the dynamics of teaching and learning.

## Installation
1. Clone the repository: `git clone https://github.com/KhalidMustafaElenani/Teaching-Learning-Based-Optimization-Algorithm.git`
2. Navigate to the project directory: `cd Teaching-Learning-Based-Optimization-Algorithm`

## Usage Examples
  - Run the PSO algorithm by executing the main.py file: `python TLBO Algorithm.ipynb`

## Example Output
```
Iteration 933:
---------------
Individual 1: [-4.95 -2.21  3.03 -1.13]    Fitness: 39.80
Individual 2: [-2.47 -1.41  1.55 -0.62]    Fitness: 10.89
Individual 3: [-2.24  0.02 -3.39  0.14]    Fitness: 16.50
Individual 4: [-3.49  4.69 -5.   -5.  ]    Fitness: 84.18
Individual 5: [ 5.   -2.42  5.    1.28]    Fitness: 57.49
-----------------------------------------------------------------
Teacher: [-2.47 -1.41  1.55 -0.62]    Fitness: 10.89
-----------------------------------------------------------------
Population Mean: [-1.63 -0.27  0.24 -1.07]
-----------------------------------------------------------------
[1] The Population After Teaching Phase:
----------------------------------------
Individual 1: [-4.74 -2.27  3.64 -0.76]    Fitness: 39.80
Individual 2: [-2.2  -1.75  1.57  0.69]    Fitness: 10.89
Individual 3: [-2.   -0.64 -3.37  0.79]    Fitness: 16.50
Individual 4: [-3.11  3.97 -4.36 -3.66]    Fitness: 84.18
Individual 5: [ 5.   -3.03  5.    1.86]    Fitness: 57.49
-----------------------------------------------------------------
Partner: [-4.74 -2.27  3.64 -0.76]
-----------------------------------------------------------------
[2] The Population After Learning Phase:
----------------------------------------
Individual 1: [-5.   -2.41  5.   -0.97]    Fitness: 39.80
Individual 2: [-2.09 -1.52 -1.92  0.73]    Fitness: 10.89
Individual 3: [-3.82 -1.4  -0.11  0.09]    Fitness: 16.50
Individual 4: [-4.44  5.   -5.   -5.  ]    Fitness: 84.18
Individual 5: [ 5.   -4.03  5.    2.17]    Fitness: 57.49

 =================================================================

Minimum Solution: [-2.09 -1.52 -1.92  0.73]    Fitness: 10.89

 =================================================================
```

## Notes
For more details on the algorithm's functionality and setup, refer to the [NOTES.md](NOTES.md).
