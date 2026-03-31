# Generalized Tic-Tac-Toe

## Introduction
This project is a fully customizable, terminal-based strategy game developed in C++20. Built upon Procedural Programming principles, the system is structured into focused modules - including a Game Engine, Game Logic, Game Interaction, Game Renderer, and a dedicated AI Bot Module to ensure clean, maintainable, and scalable code.

## Core Features
* **Dynamic Grid:** Play on an adjustable N x N board, supporting sizes from a standard 3x3 up to a massive 12x12 grid.
* **Custom Win Conditions:** Define your own rules for victory by setting the required number of consecutive symbols (from 3 up to the board's maximum size).
* **Versatile Game Modes:** Choose your playstyle with support for Player vs. Player (PVP), Player vs. Bot (PVE), and Bot vs. Bot (EVE) simulations.
* **Advanced Evaluation Rules:** The game engine rigorously checks for winning chains across horizontal, vertical, and both diagonal axes. It features configurable end-game constraints, defaulting to an `OPEN_TWO` rule where a winning sequence is only valid if both ends are unblocked.
* **Intelligent AI Opponents:**
  * **EASY:** A foundational bot that selects random, valid moves.
  * **MEDIUM:** A heuristic-driven bot programmed to actively analyze the board, prioritize immediate winning strikes, and block opponent threats.
* **Judge Mode:** Includes a specialized automated testing mode that reads pre-configured inputs from a file and outputs results in a strict, standardized format for easy grading.

## Installation & Execution
To build and run this project, ensure your environment has a compiler that supports the **C++20** standard.

## ⚙️ Installation & Execution

### 🛠️ Prerequisites
* A compiler supporting **C++20** (e.g., `g++`).
* Terminal, Command Prompt, or an IDE like Visual Studio Code.

### 🚀 Quick Start
Get the game running in seconds by executing these commands in your terminal:

 1. Clone the source code to your local machine
    ```bash
      git clone https://github.com/novafluz/Tic-Tac-Toe.git
 2. Move into the project directory
    ```bash
        cd Tic-Tac-Toe
 3. Compile the source code using C++20 standard
    ```bash
      g++ -std=c++20 -Wall -Wextra game.cpp -o game.exe
 4. Launch the game
    ```bash
    ./game.exe
