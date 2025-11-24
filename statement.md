# Project Statement: Rock-Paper-Scissors CLI Game

## 1. Problem Statement

The purpose of this assignment is to create a simple, yet rugged, command-line version of the Rock-Paper-Scissors game. In addition, the project represents an integrative assignment that aims at applying and demonstrating basic principles of Python programming with a special emphasis on the given course syllabus, namely **modular design,** effective **control flow structures** (if/else), and **reliable user input validation**.

2. Scope of the Work

The scope is limited to a single-user, session-based application.

* **In-Scope:** Core game logic, input/output interface, session-based score tracking, and comprehensive input validation.

* **Out-of-Scope:** The use of complex AI or machine learning models to predict opponents; integration of a database; development of a GUI.

3. Target Users

The major target users are:

* **The Player:** A user who wishes to play a simple, interesting game of Rock-Paper-Scissors through the command line.

* **The Evaluator/Instructor:** For evaluation of basic Python programming and modular design skills.

## 4. High-Level Features and Functional Requirements (FR)
The system consists of three major functional modules:

1. **Input/Output Interface Module (FR1):** This module handles the interaction with the user, from prompting the moves to input validation and then displaying the result of the game.

2. **Game Logic Module FR2**: Should encapsulate the core rules - if/else statements to correctly compare the player and computer moves to determine the outcome of the round: Win, Loss, or Tie.

3. **Score Tracking Module (FR3):** Keeps a dictionary-based record of the session scores for both the player and the computer, updating and displaying them after each round.
