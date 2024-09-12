# SudokuMaster

This project implements a **SudokuMaster** using a **backtracking algorithm** in **C++**. The solver can solve any 9x9 Sudoku puzzle by filling in the missing numbers based on the game's rules.

## How It Works

- The algorithm attempts to place numbers (1-9) into empty cells, checking that the number is valid in its **row**, **column**, and **3x3 subgrid**.
- If a number cannot be placed, the algorithm **backtracks** and tries a different number, ensuring all possibilities are explored to solve the puzzle.
- Once a valid number is placed in all empty cells, the Sudoku is solved.

## Code Overview

The core logic is found in two functions:
- `isValid()`: Checks whether placing a specific number in a given position is valid.
- `solveSudoku()`: Recursively attempts to solve the Sudoku puzzle using backtracking.

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/Honey3108/SudokuMaster.git
