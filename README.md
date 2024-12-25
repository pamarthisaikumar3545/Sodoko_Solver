# Sodoko_Solver

Sudoku Solver using Backtracking

This project implements a Sudoku Solver in C++ using the Backtracking Algorithm. 
The goal of the project is to solve Sudoku puzzles efficiently and demonstrate the power of backtracking for constraint satisfaction problems.

Features:

Backtracking Algorithm: Uses the backtracking technique to explore possible number placements and backtrack when a conflict arises.
Solves Standard Sudoku Puzzles: Capable of solving puzzles with a 9x9 grid, adhering to standard Sudoku rules (each row, column, and 3x3 subgrid must contain all digits from 1 to 9 without repetition).
User Input: Allows the user to input their own Sudoku puzzle and get the solution.
Visualization: The solved Sudoku grid is displayed in a clear format, showing both the initial and the final grid.

Algorithm:

The backtracking algorithm works by placing a number in an empty cell and attempting to solve the puzzle. If the number fits according to the Sudoku rules, it moves to the next cell. If it doesn't fit, the algorithm backtracks and tries a different number until the puzzle is solved.
