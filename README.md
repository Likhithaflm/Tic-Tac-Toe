# Tic-Tac-Toe
Tic-Tac-Toe using Swing, AWT
Overview
This project implements a classic Tic-Tac-Toe game using Java's Swing and AWT libraries. The game allows two players to compete against each other on a 3x3 grid, providing a simple and interactive user interface.

Key Components:

User Interface (UI):

Main Frame: The main window of the application using JFrame.
Game Board: A grid layout created with JPanel containing buttons for each cell, enabling players to make their moves.
Status Display: A label to show the current player's turn and the game result (win, loss, or draw).
Game Logic:

Grid Representation: A 2D array to track the state of the game board (empty, X, or O).
Move Validation: Logic to check if a player’s move is valid and whether it results in a win or a draw.
Turn Management: Alternating turns between players X and O.
Event Handling:

Action Listeners: Implementing ActionListener to handle button clicks and update the game state.
Game Reset: A button to reset the game, clearing the board and starting a new game.
Game Flow:

Players take turns to click on the grid buttons.
After each move, the game checks for a winner or a draw.
The UI updates to reflect the current game state, displaying appropriate messages for the players.
Code Structure:

Main Class: Initializes the game window and sets up the components.
Game Logic Class: Contains methods to manage the game state and determine outcomes.
