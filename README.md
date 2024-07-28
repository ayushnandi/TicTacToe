# Tic-Tac-Toe Game

## Introduction

This project is a simple implementation of the classic Tic-Tac-Toe game using Java and Swing for the graphical user interface. It provides a fun and interactive way to play Tic-Tac-Toe against another player on the same computer.

## Overview

The game features a 3x3 grid where players take turns marking a cell with either 'X' or 'O'. The game checks for a winner after each move and announces the winner when one player manages to align three of their marks horizontally, vertically, or diagonally. If all cells are filled without a winner, the game ends in a draw.


![image](https://github.com/user-attachments/assets/fb2e594f-1089-42ff-bd22-17805403152c)

## Tools and Components

### Java Swing
Swing is used to create the graphical user interface. It provides a rich set of components for building the game's interface, such as frames, panels, buttons, and labels.

### Components

- **JFrame**: The main window of the application.
- **JPanel**: Used for organizing other components. Two panels are used: one for the title and another for the game buttons.
- **JLabel**: Displays text, such as the game's title and whose turn it is.
- **JButton**: Represents each cell in the 3x3 grid.

### Features

- **Random Turn Selection**: The game randomly selects which player goes first.
- **Action Listener**: Handles button clicks to mark the cells and check for a win condition.
- **Win Checking**: After each move, the game checks all possible win conditions to determine if a player has won.
- **Disable Buttons on Win**: Once a player wins, all buttons are disabled to prevent further moves.

## How It Works

1. **Initialization**:
   - The main window (JFrame) is set up with a title panel and a button panel.
   - Nine buttons (JButton) are added to the button panel to represent the 3x3 grid.

2. **First Turn**:
   - The game randomly selects which player (X or O) will go first.

3. **Gameplay**:
   - Players take turns clicking on the buttons to mark their moves.
   - After each move, the game checks if there is a winner by evaluating all possible win conditions.

4. **Win Condition**:
   - If a player wins, the winning buttons are highlighted, and a message is displayed.
   - All buttons are disabled to prevent further moves.

## Running the Game

To run the game, compile and execute the `TicTacToe` class. Ensure you have the necessary Java development environment set up.

```bash
javac TicTacToe.java
java TicTacToe
