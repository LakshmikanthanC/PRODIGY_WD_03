﻿# PRODIGY_WD_03
Tic-Tac-Toe Game*

#### Description
This is a simple implementation of the classic Tic-Tac-Toe game. The game is developed using HTML, CSS, and JavaScript and is designed for two players. Players take turns marking spaces in a 3x3 grid, and the first player to align three of their marks horizontally, vertically, or diagonally wins. If all spaces are filled and no player has achieved alignment, the game ends in a draw.

#### Features
- Interactive 3x3 grid for gameplay.
- Alternating turns between Player X and Player O.
- Detection of winning or draw conditions.
- Reset button to restart the game.

#### Technology Stack
- *HTML*: For structuring the layout of the game board.
- *CSS*: For styling the game board and buttons.
- *JavaScript*: For game logic, turn management, and win/draw detection.

#### How to Play
1. Open the index.html file in a web browser.
2. The game starts with Player X's turn.
3. Click on an empty cell in the grid to mark it.
4. The game announces a winner or a draw once the condition is met.
5. Use the reset button to play a new game.

#### How It Works
1. *HTML*: Provides a structured grid layout using a div container. Each cell in the grid is represented by a button or a div.
2. *CSS*: Ensures a visually appealing design with hover effects and distinct markings for X and O.
3. *JavaScript*: Handles:
   - Tracking player turns.
   - Checking the game board for win or draw conditions after each turn.
   - Resetting the game board when needed.

#### File Structure

- index.html  // Main HTML file
- styles.css  // CSS for styling
- script.js   // JavaScript for game logic


#### Future Improvements
- Add an AI player for single-player mode.
- Enhance the UI/UX with animations and sound effects.
- Keep a scoreboard to track wins, losses, and draws.
- Make the game mobile-friendly using responsive design.
