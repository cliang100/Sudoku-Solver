---

# Sudoku Solver

## Introduction
This is a Python program that solves Sudoku puzzles using a backtracking algorithm. Sudoku is a popular logic-based number puzzle where the objective is to fill a 9x9 grid with digits so that each column, each row, and each of the nine 3x3 subgrids contain all of the digits from 1 to 9.

## How to Use
1. Ensure you have Python installed on your system.
2. Run the `sudoku.py` file using Python.
3. The Sudoku puzzle to be solved should be represented as a 9x9 grid, where empty cells are represented by the value `-1`.
4. Define the puzzle in the `example_board` variable in the code.
5. Execute the program, and it will print the solved Sudoku puzzle.

## Example
An example Sudoku puzzle is provided in the `example_board` variable in the code. You can replace this with any Sudoku puzzle you want to solve.

## Notes
- The solver utilizes a backtracking algorithm to recursively explore all possible solutions.
- If the puzzle has multiple solutions, the solver will find one of them.
- Ensure that the input Sudoku puzzle is valid and has a unique solution.

---
