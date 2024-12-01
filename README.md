# **Tic-Tac-Toe** 🎮 

Welcome to the Tic-Tac-Toe game project! This repository contains a fully functional two-player Tic-Tac-Toe game built using Java. The project demonstrates key concepts of Object-Oriented Programming (OOP), software design patterns, and clean code principles.

### 📖 **Introduction**

Tic-Tac-Toe is a classic game played between two players. The goal is to place three of your marks (X or O) in a row, either horizontally, vertically, or diagonally, on a 3x3 grid before your opponent does. This project is implemented in Java and focuses on clean, modular design and code readability.

### 🎯**Design and Features**

Core Features
- Two-Player Gameplay:
The game allows two players to compete in a turn-based manner.

- Interactive Console Interface:
The game provides a simple, text-based interface for players to interact with.

- Real-Time Board Updates:
The board is updated and displayed after each move, reflecting the current state of the game.

- Automatic Win/Draw Detection:
The game automatically detects if a player has won or if the game ends in a draw.

### 🚀 **Getting Started**

Follow the instructions below to set up and run the project on your local machine.

Prerequisites

- Java Development Kit (JDK) 8 or higher.
- IDE: IntelliJ IDEA, Eclipse, or any code editor with Java support.

### 🎮 **Gameplay**

1. Game Start:
Players are prompted to enter their names and choose their symbols (X or O).
  
3. Taking Turns:
Players take turns entering their moves by specifying the row and column of the cell where they want to place their symbol.

  - Example: Enter 1 2 to place your mark in the first row and second column.

4. Displaying the Board:
After each move, the current state of the board is displayed.

6. Game End:
The game ends when a player wins or the board is full, resulting in a draw.

### 🏆 **Win Conditions**

A player wins if they place three of their symbols consecutively in any of the following ways:

- Horizontal: Three symbols in a row.
- Vertical: Three symbols in a column.
- Diagonal: Three symbols in a diagonal.

### 🧠 **Design Patterns**

This project follows the Model-View-Controller (MVC) design pattern:

- Model: Manages the game state, players, and board (Game.java, Board.java, Player.java).
- View: Displays the game board and prompts players via the console.
- Controller: Controls the game flow from start to end (Main.java).

### 📈 **Future Enhancements**

 - AI Player: Add a single-player mode with an AI opponent using the Minimax algorithm.
 - GUI Support: Implement a graphical user interface using JavaFX or Swing.
 - Custom Board Size: Allow players to select different board sizes (e.g., 4x4, 5x5).
 - Score Tracking: Maintain a scoreboard across multiple game sessions.
 - Multiplayer Support: Enable network-based multiplayer functionality.
