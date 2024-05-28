# Tic Tac Toe Game

### Project Overview

This project is a simple implementation of the classic two-player Tic-Tac-Toe game. One player plays as "x" and the other as "o". Players take turns placing their marks on a 3x3 grid. The objective is to be the first to get three marks in a row, either horizontally, vertically, or diagonally, to win the game.

### Tools

- Python

### Features

- **Two-Player Mode:** Play against another person locally.
- **Command Line Interface:** Simple and intuitive text-based gameplay.
- **Winning Detection:** Automatically checks for a winner after each turn.
- **Input Validation:** Ensures players enter valid moves.
- **Game Reset:** Option to restart the game after a win or draw.
- **Turn Indicator:** Clearly indicates which player's turn it is.
- **Score Tracking:** Keeps track of wins for each player across multiple games.
- **Minimal Dependencies:** No need for external libraries beyond the Python standard library.

### How It Works

1. **Starting the Game:**
   - When you run the `tic_tac_toe.py` script, the game initializes and displays a blank 3x3 grid in the terminal.

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

   - Players take turns entering the number of the cell where they want to place their mark. For example, Player x might enter 1 to place an X in the top-left corner.

4. **Displaying Moves:**
   - After each move, the grid updates to reflect the current state of the game. For example, if Player x chooses cell 1 and Player o chooses cell 5, the grid will update as follows:
```
  |   |  
--|---|--
  | o |  
--|---|--
x |   |
```

5. **Turn Indicator:**
   - The game clearly indicates which player's turn it is by displaying a prompt like “Player x’s turn” or “Player o’s turn.”

6. **Winning Detection and Announcements:**
   - The game automatically checks for a winning condition after each move. If a player gets three marks in a row, the game announces the winner and displays the winning grid.
  
7. **Draw Condition:**
   - If all cells are filled and no player has won, the game declares a draw.

8. **Restarting the Game:**
   - After a win or a draw, the game prompts players to either restart or exit. Players can choose to play another round or quit the game.
 

