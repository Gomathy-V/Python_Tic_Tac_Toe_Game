# Tic Tac Toe Game

### Project Overview

This project is a simple implementation of the classic two-player Tic-Tac-Toe game. One player plays as "x" and the other as "o". Players take turns placing their marks on a 3x3 grid. The objective is to be the first to get three marks in a row, either horizontally, vertically, or diagonally to win the game.

### Tools

- Python
- Jupyter Notebook

### Features

- **Two-Player Mode:** Play against another person locally.
- **Command Line Interface:** Simple and intuitive text-based gameplay.
- **Winning Detection:** Automatically checks for a winner after each turn.
- **Input Validation:** Ensures players enter valid moves.
- **Game Reset:** Option to restart the game after a win or draw.
- **Smooth Player Transition:** Seamless switching between players ensures uninterrupted gameplay.
- **Score Tracking:** Keeps track of wins for each player across multiple games.
- **Minimal Dependencies:** No need for external libraries beyond the Python standard library.

### How It Works

1. **Starting the Game:**
   - When you run the `tic_tac_toe.ipynb` script, the game initializes and displays a blank 3x3 grid in the terminal.

2. **Game Grid Representation:**
   - The empty grid is displayed with cells represented by their row and column indices. For example:
```
  |   |  
--|---|--
  |   |  
--|---|--
  |   |
```

3. **Player Input:**

   - Players take turns entering the number of the cell where they want to place their mark. For example, Player x might enter 1 to place an x in the bottom-left corner.

4. **Displaying Moves:**
   - After each move, the grid updates to reflect the current state of the game. For example, if Player x chooses cell 1 and Player o chooses cell 5, the grid will update as follows:
```
  |   |  
--|---|--
  | o |  
--|---|--
x |   |
```

5. **Smooth Player Transition:**
   - This feature automatically alternates between Player x and Player o after each move, providing clear prompts and eliminating the need for manual tracking.

6. **Winning Detection and Announcements:**
   - The game automatically checks for a winning condition after each move. If a player gets three marks in a row, the game announces the winner.
  
7. **Draw Condition:**
   - If all cells are filled and no player has won, the game declares a draw.

8. **Restarting the Game:**
   - After a win or a draw, the game prompts players to either restart or exit. Players can choose to play another round or quit the game.
 

