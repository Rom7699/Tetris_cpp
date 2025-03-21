# Tetris Game Simulation

## Overview
A classic Tetris game implementation in C++ featuring two-player support, customizable color modes, and multiple shape configurations. This object-oriented project allows players to compete against each other to clear lines and achieve the highest score.

## Features
- **Two-player mode** with separate controls and independent score tracking
- Dynamic shape generation and movement
- Adjustable color modes and game speeds
- Interactive menus for game control, instructions, and pause functionality
- Comprehensive game-over logic with high score tracking

## Components
The project is structured around the following components:

- **Main Game** (`main.cpp`): Initializes the game and starts the main game loop
- **Game Configuration** (`GameConfig.cpp`, `GameConfig.h`): Manages game settings, controls, and display configurations
- **Board** (`Board.cpp`, `Board.h`): Represents the game board, manages the placement of shapes, checks for full rows, and handles scoring
- **Top Board** (`TopBoard.cpp`, `TopBoard.h`): Displays the score and player information at the top of the game screen
- **Shape** (`Shape.cpp`, `Shape.h`): Defines the various Tetris shapes, manages their movements, rotations, and drawing on the screen
- **Point** (`Point.cpp`, `Point.h`): Handles individual point positions on the board and their visual representation
- **Tetris Game Logic** (`TetrisGame.cpp`, `TetrisGame.h`): Contains the core game loop, menu displays, pause handling, and game-over conditions

## Controls

### Player 1
- **Left**: `a` or `A`
- **Right**: `d` or `D`
- **Rotate Clockwise**: `w` or `W`
- **Rotate Counter-Clockwise**: `s` or `S`
- **Hard Drop**: `x` or `X`
- **Pause**: `ESC`

### Player 2
- **Left**: `j` or `J`
- **Right**: `l` or `L`
- **Rotate Clockwise**: `i` or `I`
- **Rotate Counter-Clockwise**: `k` or `K`
- **Hard Drop**: `m` or `M`
- **Pause**: `ESC`

## Requirements
- C++ compiler that supports C++11 or higher
- Windows OS for `conio.h` and `Windows.h` dependencies (or suitable alternatives on other platforms)
