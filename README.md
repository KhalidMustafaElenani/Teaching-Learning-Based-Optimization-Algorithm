## Description
This repository contains a Python implementation of the Teaching Learning-based Optimization (TLBO) algorithm. TLBO is a stochastic population-based optimization method inspired by classroom learning dynamics. In TLBO, individuals in a population act as both teachers and learners, engaging in iterative knowledge transfer to evolve solutions.

The algorithm consists of two main phases:
1. **Teacher Phase**: Generates new solutions based on the best solution and the population mean, followed by a greedy selection process.
2. **Learner Phase**: Creates new solutions using a partner solution, followed by another greedy selection process.

This method is used for solving various optimization problems by leveraging the dynamics of teaching and learning.

## Code Overview
- **`tlbo_algorithm.py`**: 
  - Implements the TLBO algorithm including both teacher and learner phases.

For more details on the algorithm's functionality and setup, refer to the [NOTES.md](NOTES.md).
