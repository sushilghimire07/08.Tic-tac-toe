# Tic-Tac-Toe Game

This is a simple Tic-Tac-Toe game implemented in JavaScript, HTML, and CSS. The game features a human player vs. AI player (using the Minimax algorithm).

## Features

- Human player ("O") vs. AI player ("X")
- Dynamic game board
- AI opponent using the Minimax algorithm
- End game detection with win or tie message

## Files

- `index.html`: The HTML file containing the game structure.
- `style.css`: The CSS file for styling the game board and end game message.
- `script.js`: The JavaScript file containing the game logic and Minimax algorithm.

## Usage

### Starting the Game

1. Open `index.html` in your web browser.
2. Click on any cell to make a move. You play as "O".
3. The AI will automatically make a move as "X".

### Game Logic

- The game board is represented as a 3x3 grid.
- Players take turns to mark a cell.
- The first player to align three marks in a row (horizontally, vertically, or diagonally) wins.
- If all cells are filled without any player aligning three marks, the game ends in a tie.

### Minimax Algorithm

The AI uses the Minimax algorithm to determine the best move:
- The algorithm recursively simulates all possible moves and selects the move with the highest score for the AI player.
- Scores are assigned based on win/loss/tie outcomes to maximize the AI's chances of winning.

