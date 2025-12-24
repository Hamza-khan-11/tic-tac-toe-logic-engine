**Tic-Tac-Toe Logic Engine**

A clean, functional implementation of the classic Tic-Tac-Toe game built
with Python. This project focuses on back-end logic, utilizing a
dictionary-based coordinate system to track moves and verify victory
conditions across rows, columns, and diagonals.

**Project Overview**

This engine provides a robust framework for a turn-based strategy game.
It manages player inputs, ensures that moves are only made in valid
empty spaces, and continuously monitors the board for three possible
outcomes: a Win for Player 1, a Win for Player 2, or a Draw.

**Key Features**

Dynamic Board Mapping: Uses a dictionary (1--9) to represent the grid,
making the code highly readable and easy to map to a numeric keypad.

Recursive Validation: Includes a spaceIsFree check that prevents
overwriting moves, recursively prompting the user until a valid input is
received.

Comprehensive Win Logic: A multi-conditional check covers all 8 possible
winning lines (3 horizontal, 3 vertical, and 2 diagonal).

Game State Management: Automatically detects \"Draw\" scenarios when the
board is full and no winner is found.

**Tech Stack**

Language: Python 3.x

Data Structures: Dictionary-based state tracking.

**How to Play**

**Prerequisites**

You only need Python installed. No external libraries (like NumPy or
OpenCV) are required for this core logic version.

**Running the Game**

-   Clone this repository

-   Run this script

-   Controls: Enter a number between 1 and 9 to place your mark on the
    corresponding board position

1\|2\|3

-+-+-

4\|5\|6

-+-+-

7\|8\|9
