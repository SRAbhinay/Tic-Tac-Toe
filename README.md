# Tic-Tac-Toe

This Python code represents a simple implementation of a Tic-Tac-Toe game between a human player and a computer opponent. The code utilizes a 3x3 grid as the game board and alternates between the player and the computer making moves until one of them wins or the game ends in a tie. Here's a brief description of its logic and special features:

Logic:

The game is played on a 3x3 grid, with the player as "O" and the computer as "X."
The player and computer take turns making moves.
The game checks for a win condition after each move.
The player can input their move by specifying the position (1-9) where they want to place their "O."
The computer's moves are generated randomly from the available empty spots on the board.
Specialties:

The game board is displayed after each move to provide a visual representation of the game's progress.
Input validation ensures that the player's move is within the valid range (1-9) and that the chosen cell is not already occupied.
The code includes a basic victory-checking mechanism that verifies rows, columns, and diagonals for a win condition.
It handles ties when the game grid is completely filled without a winner.
The computer's moves are randomized using the randrange function, making each game unique.
The code is well-structured and commented to improve readability and understanding.
