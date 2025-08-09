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

### Running the game with `start.bat`

You can start the game easily by double-clicking the `start.bat` file, which will launch the game automatically.

---

### Running the game manually via Command Prompt (CMD)

1. Open **Command Prompt** (CMD).

2. Navigate to the folder where the game files are located. For example, if your game folder is in `C:\Games\Sudoku`, type:

    ```cmd
    cd C:\Games\Sudoku
    ```
    and press **Enter**.

3. Run the Python script by typing:

    ```cmd
    python sudoku.py
    ```
    and press **Enter**.
   
Make sure Python is installed and added to your system’s PATH so that the `python` command works.

---

Enjoy playing!
