# TicTacToe-Game

#Description:
This repository contains a fully implemented Tic-Tac-Toe game built in Java using the Swing framework, showcasing clean object-oriented design, responsive UI handling, and event-driven programming. The project is designed to demonstrate how a classic game can be developed using Java Swing components, layout managers, and custom game logic, making it an excellent example for beginners and intermediate developers learning GUI programming in Java.

The game features a polished 3×3 grid interface built with JButton components, dynamic turn switching between Player X and Player O, and complete detection for horizontal, vertical, and diagonal wins, as well as tie conditions. The program’s architecture separates the entry point (App.java) from the main game logic (TicTacToe.java), following clean coding practices.

Internally, the game leverages:

ActionListeners to handle user clicks and update the board state

GridLayout to render a symmetrical, responsive button layout

Color-coded UI cues to distinguish active states and winning lines

Immutable end-game states that lock the board once a winner is determined

Efficient win-check algorithms which scan all possible victory combinations

This project runs on any system with Java installed and requires no additional libraries. It serves as a practical example for:

Event-driven GUI programming

Swing component manipulation

Java OOP fundamentals

Real-time state updates in games

Beginner-friendly game logic design
