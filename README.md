# 8-Queens

- **Evolutionary Computation Homework (Fall 2023)**
- [Click](https://github.com/matinmonshizadeh/8-Queens/blob/main/Doc.pdf)  to see additional details.
- ![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=306998)

## Introduction
The N-queens problem was introduced in 1850 by Carl Gauss and has been studied for many decades
by scientists. The 8-queens problem is an effort to find a placement of 8 queens on an 8 x 8 chess board
so that no two queens attack each other. The queens should be placed on the chessboard in a way that
these conflicts are minimized — no two queens should be in the same row, column, or diagonal.

## Properties

In this assignment, I had to implement an evolutionary solution for the 8-queens problem. I applied a genetic algorithm (GA) with the properties listed below to solve the problem:

- **Representation**: Premutation
- **Recombination**: ‘Cut-and-Fill’ crossover
- **Recombination probability**: 100%
- **Mutation**: Swap
- **Mutation probability**: 80%
- **Parent selection**: Best 2 out of random 5
- **Survival selection**: replace children with the 2 worse individuals in population.
- **Population size**: 100
- **Number of offspring**: 2
- **Initialization**: Random
- **Termination condition**: Solution or 10,000 fitness evaluations
