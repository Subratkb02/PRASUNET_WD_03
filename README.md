PRASUNET_WD_03

Overview:

It is a simple  Tic-Tac-Toe game developed using HTML, CSS, and JavaScript. The game allows two players to take turns marking spaces in a 3x3 grid with "X" or "O". The winner is the first player to align three of their marks in a horizontal, vertical, or diagonal row.

Features:

-Two-player Mode: Alternates turns between Player O and Player X.
-Win Detection: Automatically detects and announces the winner based on predefined win patterns.
=Draw Detection: Declares the game a draw if all nine cells are filled without a winner.
=Reset Functionality: Allows players to reset the game and start over.
=Visual Feedback: Changes the color of the marks to enhance the user experience.

How It Works:

Game Setup:

HTML and CSS set up the basic structure and styling of the game board.
JavaScript manages game logic and interactivity.

Event Handling:

Each cell (box) on the board listens for click events to register a player's move.
The game alternates turns between Player O and Player X, updating the cell's text and color accordingly.
Moves are counted and checked against predefined win patterns to determine a winner.

Game Logic:

-checkWinner(): Evaluates the board state against all possible win patterns.
-drawGame(): Checks if all cells are filled without a winner and declares a draw.
-resetGame(): Resets the game state, enabling all cells and clearing their content.

UI Updates:

The game displays messages in a message container to announce the winner or a draw.
The game board is disabled when a win or draw condition is met to prevent further moves until reset.

Usage:

-Clone the repository: git clone https://github.com/Subratkb02/PRASUNET_WD_03
-Open index.html in a web browser.
-Click on any cell to start the game.
-Take turns clicking cells to mark "O" or "X".
-Click the reset button to start a new game.

Conclusion:

It is an engaging and interactive Tic-Tac-Toe game that showcases basic web development skills using HTML, CSS, and JavaScript. It provides a fun way to practice game logic and UI interaction.
