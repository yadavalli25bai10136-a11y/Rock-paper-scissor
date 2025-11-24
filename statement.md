# Project Statement: Rock-Paper-Scissors CLI Game

## 1. Problem Statement

My friend keeps beating me at Rock Paper Scissors. I need a new opponent - one I can actually beat. Build me a computer player that's fair, random, and won't gloat when it wins.

2. Scope of the Work

The scope is limited to a single-user, session-based application.

* **In-Scope:** Core game logic, input/output interface, session-based score tracking, and comprehensive input validation.

* **Out-of-Scope:** The use of complex AI or machine learning models to predict opponents; integration of a database; development of a GUI.

3. Target Users

The major target users are:

* **The Player:** A user who wishes to play a simple, interesting game of Rock-Paper-Scissors through the command line.

* **The Evaluator/Instructor:** For evaluation of basic Python programming and modular design skills.

## 4. High-Level Features and Functional Requirements (FR)
The system includes three major functional modules:

FR1: Input/Output Interface Module - This module is responsible for the interaction with the user, from prompting the moves, input validation, up to displaying the result of the game.

Game Logic Module FR2: The module should encapsulate the core rules, the logic for performing the if/else statements that accurately compare the player and computer moves to identify the outcome of the round: Win, Loss, or Tie.

FR3 - Score Tracking Module: Maintains session scores for both player and computer in dictionary format and displays updated values after every round.
