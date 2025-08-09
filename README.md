# Sudoku Game by Luka-M. S.

A simple Sudoku puzzle game with a graphical user interface (GUI) built in Python using Tkinter.  
It features a Sudoku generator and solver based on a backtracking algorithm.

## Features

- Generates a complete Sudoku board and creates puzzles of varying difficulty levels:
  - Easy
  - Medium
  - Hard
- Interactive 9x9 grid using Entry widgets for number input (1-9).
- Toolbar with buttons for:
  - Restarting the game with a new puzzle
  - Selecting difficulty level
  - Checking the current solution for correctness
  - Revealing the complete solution
- Highlights incorrect cells when checking the solution.
- Input validation to accept only numbers 1 through 9.
- User-friendly and responsive interface.

## How it works

1. The game generates a fully solved Sudoku board using a backtracking algorithm.
2. Cells are removed based on the chosen difficulty to create a puzzle.
3. The player fills in the empty cells.
4. The player can check their solution or ask the program to solve the puzzle and display the solution.

## Usage

Simply start the game by running the start.bat file — the game will launch automatically.

```bash
python sudoku.py
