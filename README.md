# SUDOKU SOLVER
## Description


This Python script implements a Sudoku solver using a backtracking algorithm. It can solve standard 9x9 Sudoku puzzles.



## Features

- Backtracking algorithm for solving Sudoku puzzles.
- Supports 9x9 grids.
- Outputs the solved Sudoku grid.



## Usage

- Open the script file sudoku_solver.py.
- Modify the grid variable with the Sudoku puzzle you want to solve.
- Run the script.
- The solved Sudoku grid will be printed if a solution is found



# Code explanation

### is_valid_move(grid, row, col, number)
- Checks if placing a given number at a specific position (row, col) in the Sudoku grid is a valid move.
- Validates against Sudoku rules for rows, columns, and 3x3 subgrids.

### solve(grid, row, col)
- Recursive function that attempts to solve the Sudoku grid using backtracking.
- Iterates through each cell in the grid, placing numbers and backtracking if a valid solution is not found.



## License

This project is licensed under the MIT License.

**Free Software, Hell Yeah!**


