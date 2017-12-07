
# Project Title 
Diagonal Sudoku Solver
## Introduction
This was my first project in Artificial Intelligence Nanodegree Term-1. In this project, the code was written to implement the two extensions of our sudoku solver. The first one implemented the technique called "naked twins". The second  modified the existing code to solve a diagonal sudoku. 

The concepts of "Naked Twins" and "Diagonal Sudoku" can be explained as:
#### Question 1 (Naked Twins)
Q: How do we use constraint propagation to solve the naked twins problem?  
A: Examine each unit and check for naked twins(pairs of length 2). If present then no other box in the unit can contain the 2 digits in each pair. Remove the 2 digits from other unsolved peers in the unit.

#### Question 2 (Diagonal Sudoku)
Q: How do we use constraint propagation to solve the diagonal sudoku problem?  
A: Add the 2 diagonal units to the unitlist. This will result in additional units and peers for the boxes on the diagonals. These additional constraints will help reduce the solution space when trying to solve a puzzle.  

### Install

This project requires **Python 3**.

Installed [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project. 


### Code

* `solutions.py` - Code for solution of the given problem.
* `solution_test.py` - It consists of the test cases for our solution. We can test our solution by running `python solution_test.py`.
* `PySudoku.py` - Do not modify this. This is code for visualizing our solution.
* `visualize.py` - Do not modify this. This is code for visualizing our solution.


### Data

The data consists of a text file of diagonal sudokus, provided for us to solve.
