**Sudoku Solver**

This Python script implements a Sudoku solver using a backtracking algorithm. Sudoku is a popular puzzle game where the objective is to fill a 9x9 grid with digits so that each column, each row, and each of the nine 3x3 subgrids contain all of the digits from 1 to 9.

**Usage:**

To use the Sudoku solver, pass a 9x9 puzzle board represented as a list of lists to the `solve_sudoku` function. Here's an example:

```python
if __name__ == '__main__':
    puzzle = [
      [0, 0, 2, 0, 0, 8, 0, 0, 0],
      [0, 0, 0, 0, 0, 3, 7, 6, 2],
      [4, 3, 0, 0, 0, 0, 8, 0, 0],
      [0, 5, 0, 0, 3, 0, 0, 9, 0],
      [0, 4, 0, 0, 0, 0, 0, 2, 6],
      [0, 0, 0, 4, 6, 7, 0, 0, 0],
      [0, 8, 6, 7, 0, 4, 0, 0, 0],
      [0, 0, 0, 5, 1, 9, 0, 0, 8],
      [1, 7, 0, 0, 0, 6, 0, 0, 5]
    ]

    solve_sudoku(puzzle)
```

This will print the unsolved puzzle, solve it using the Sudoku solver, and print the solved puzzle.

**Features:**

- The `Board` class represents the Sudoku board and provides methods for solving the puzzle.
- The `solver()` method uses backtracking to recursively solve the Sudoku puzzle.
- If the puzzle is solvable, the solver prints the solved puzzle. Otherwise, it prints a message indicating that the puzzle is unsolvable.

**Note:**

- The script utilizes a backtracking algorithm to efficiently solve Sudoku puzzles.
- The solution process is printed step by step, showing the initial puzzle and the solved puzzle.
- If the provided puzzle is unsolvable, the script will notify the user.

**Dependencies:**

- This script does not require any external dependencies. It utilizes only built-in Python functionalities.

**Contributing:**

- Contributions to improve the efficiency or readability of the code are welcome. Feel free to submit a pull request on the GitHub repository.
