# Chess AI Project

## Table of Contents
1. [Overview](#overview)  
2. [Features](#features)  
3. [Data Structures and Algorithms](#data-structures-and-algorithms)  
   - [Data Structures](#data-structures)  
   - [Algorithms](#algorithms)  
4. [Optimization Techniques](#optimization-techniques)  
5. [Performance Analysis](#performance-analysis)  
6. [Setting Up the Environment](#setting-up-the-environment)  
   - [Install Python](#install-python)  
   - [Install Required Libraries](#install-required-libraries)  
   - [Troubleshoot Installation Issues](#troubleshoot-installation-issues)  
7. [Usage](#usage)  

---

## Overview  
This project is a **Chess AI game** developed in Python, integrating advanced algorithms and data structures to create an intelligent and challenging opponent for human players. The game supports both **Human vs Human** and **Human vs AI** modes, providing a comprehensive chess playing experience.

---

## Features  
- **Human vs Human mode**  
- **Human vs AI mode** with a challenging AI opponent  
- **Move validation** and enforcement of chess rules  
- **Special moves support**: castling, en passant, and pawn promotion  
- **Check and checkmate detection**  
- **Move history** and undo functionality  
- **GUI** developed using **Pygame** for an interactive experience  

---

## Data Structures and Algorithms

### Data Structures  
- **Dictionary**: Stores the current state of each position on the chessboard for efficient access and updates.  
- **List**: Tracks legal moves, captured pieces, and move history.  
- **Stack**: Manages move history to facilitate undo operations.  
- **Queue**: Handles events and actions in a first-in, first-out (FIFO) order.  
- **Tree**: Utilized in the minimax algorithm to explore possible game states and moves.  
- **Tuple**: Captures and stores the state of moves, ensuring immutability.  
- **Graph**: Represents the chessboard and piece movements.  

### Algorithms  
- **Minimax Algorithm with Alpha-Beta Pruning**:  
  - **Time Complexity**: O(b^d), where b is the branching factor and d is the depth of the search tree.  
  - **Space Complexity**: O(bd), for storing the game tree and recursive call stack.  
- **BFS/DFS**: Used for the movement of chess pieces like the queen, rook, and bishop.  

---

## Optimization Techniques  
- **Alpha-Beta Pruning**: Enhances the minimax algorithm by pruning branches that do not affect the final decision, optimizing performance.  
- **Move Ordering**: Prioritizes capturing moves and checks to increase the efficiency of alpha-beta pruning.  
- **State Restoration**: Uses tuples to store and restore board states efficiently during move simulations.  

---

## Performance Analysis  
- The chess AI efficiently evaluates board states and makes informed decisions, providing a challenging opponent for human players.  
- Optimized algorithms ensure quick response times and smooth gameplay.  

---

## Setting Up the Environment

### Install Python  
- Download and install **Python 3.8** or later from the [official Python website](https://www.python.org).  
- During installation, make sure to check the option **“Add Python to PATH”** to make Python accessible from the command line.  

### Install Required Libraries  
- Open a terminal or command prompt and run the following command to install the Pygame library:  
  ```bash
  pip install pygame
