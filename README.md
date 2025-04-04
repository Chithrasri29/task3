 🧩 Sudoku Solver (9x9) - Python

This project is a Python program that solves any standard 9x9 Sudoku puzzle using the **backtracking algorithm**. In Sudoku, each row, column, and 3x3 subgrid must contain the numbers **1 through 9** without repetition. The puzzle is represented as a 9x9 grid using a list of lists, where **0 denotes empty cells** that need to be filled.

The solution is built upon a combination of utility functions: `is_valid()` checks whether placing a number in a specific cell follows Sudoku rules, while `find_empty()` scans the grid to locate the next unfilled cell. The core function, `solve_sudoku()`, applies the backtracking approach—attempting to fill empty cells one by one, validating each move, and backtracking if a conflict arises.

Once a valid solution is found, the `print_board()` function neatly displays the completed grid. This project highlights algorithmic thinking, recursion, and fundamental Python programming techniques. It's a great example of how logical reasoning and coding can come together to solve complex puzzles efficiently.
