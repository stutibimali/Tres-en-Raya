# Tic-Tac-Toe Game in C

A simple command-line-based **Tic-Tac-Toe** game written in C for two players. Players alternate turns to mark X or O on a 3x3 grid, and the game ends when one player wins or the grid is filled with no winner (draw).

## Features
- Two-player gameplay (Player 1 = X, Player 2 = O)
- Interactive board display
- Input validation for selecting grid positions
- Determines winner or a draw
- Alternates player turns

## Requirements
- A C compiler (e.g., GCC)
- Standard C library

## Game Flow
1. The game starts by displaying a 3x3 grid with numbers 1 to 9.
2. Players alternate marking X or O in available spots by entering a number between 1 and 9.
3. The game checks if there's a winner or a draw after each move.
4. The game ends when one player wins, or the grid is full with no winner.

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/tic-tac-toe-c.git
2. Navigate to the project directory:
    ```cd tic-tac-toe-c
3. Compile the C code:
   ```gcc -o tic-tac-toe main.c
4. Run the game:
   ```/main

## Gameplay Instructions
Player 1 (X) starts the game by choosing a number between 1 and 9 corresponding to the grid position.
Player 2 (O) will then take their turn.
The game will print the board after each turn and notify the players if there’s a winner or a draw.
To input a move, simply enter the number corresponding to an empty space on the grid.

