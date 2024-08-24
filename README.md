__Sudoku Solver__
This repository contains a Python implementation of a Sudoku solver using a backtracking algorithm. The code solves Sudoku puzzles by filling in the grid while adhering to Sudoku rules.

**Features**
Find Next Empty Cell: Identifies the next cell in the puzzle that is empty (represented by -1).
Validate Guess: Checks whether placing a number in a specific cell is valid according to Sudoku rules.
Solve Sudoku: Uses a backtracking algorithm to solve the puzzle, modifying the grid to reflect the solution if one exists.

**Functions**
find_next_empty(puzzle): Finds the next empty cell in the Sudoku puzzle. Returns a tuple of row and column indices, or (None, None) if the puzzle is complete.

is_valid(puzzle, guess, row, col): Determines if placing a number (guess) in the specified cell (row, col) is a valid move. Returns True if valid, otherwise False.

solve_sudoku(puzzle): Solves the Sudoku puzzle using backtracking. Modifies the puzzle in place and returns True if a solution is found, otherwise False.

**License**
This project is open-source and available under the MIT License.

**Contributions**
Contributions are welcome! Feel free to submit issues or pull requests to enhance the solver.
