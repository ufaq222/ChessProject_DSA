# Chess Project  
**Subject Code:** CSC200 - Data Structures and Algorithms  
**Instructor:** Prof. Nazeef Ul Haq and Prof. Waseem  

## Contributions  
- Hira Sohail  
- Khadiha Saeed  
- Ufaq Hafeez  
- Ayesha Wasim  

---

## Table of Contents  
1. [Overview](#overview)  
2. [Features](#features)  
3. [Technologies Used](#technologies-used)  
4. [Data Structures and Algorithms](#data-structures-and-algorithms)  
    - [Data Structures](#data-structures)  
    - [Algorithms](#algorithms)  
5. [Optimization Techniques](#optimization-techniques)  
6. [Performance Analysis](#performance-analysis)  
7. [Setting up the Environment](#setting-up-the-environment)  
    - [Install Python](#install-python)  
    - [Install Required Libraries](#install-required-libraries)  
    - [Troubleshoot Installation Issues](#troubleshoot-installation-issues)  
    - [Clone the Repository](#clone-the-repository)  
8. [Conclusion](#conclusion)  

---

## Overview  
This project is a Chess AI game developed in Python, integrating advanced algorithms and data structures to create an intelligent and challenging opponent for human players. The game supports both Human vs Human and Human vs AI modes, providing a comprehensive chess-playing experience.  

---

## Features  
- **Human vs Human mode**  
- **Human vs AI mode** with a challenging AI opponent  
- Move validation and enforcement of chess rules  
- Support for special moves: castling, en passant, and pawn promotion  
- Check and checkmate detection  
- Move history and undo functionality  
- GUI developed using Pygame for an interactive experience  

---

## Technologies Used  
- **Python**: Core programming language used for game logic and AI.  
- **Pygame**: Library used for developing the graphical user interface.  
- **Minimax Algorithm**: Used for AI decision-making.  
- **Alpha-Beta Pruning**: Optimization technique for the minimax algorithm.  

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
    - **Time Complexity**: O(b^d), where *b* is the branching factor and *d* is the depth of the search tree.  
    - **Space Complexity**: O(bd), for storing the game tree and recursive call stack.  
- **BFS/DFS**: Used for the movement of chess pieces like queens, rooks, and bishops.  

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

## Setting up the Environment  

### Install Python  
1. Download and install Python 3.8 or later from the [official Python website](https://www.python.org/).  
2. During installation, make sure to check the option **“Add Python to PATH”** to make Python accessible from the command line.  

### Install Required Libraries  
1. Open a terminal or command prompt and run the following command to install the Pygame library:  
    ```bash
    pip install pygame
    ```  
2. The `sys` library is part of Python's standard library and is included by default, so no installation is required.  

### Troubleshoot Installation Issues  
- If you face issues, ensure Python is added to your system’s PATH.  
    - To check, type `python --version` in the terminal.  
    - If it doesn’t show the version, reinstall Python and check the **“Add to PATH”** option during setup.  
- If `pip` isn’t recognized, refer to the [pip documentation](https://pip.pypa.io/en/stable/).  

### Clone the Repository  
1. Run the following command in your terminal to clone the repository:  
    ```bash
    git clone https://github.com/ufaq222/ChessProject_DSA.git
    ```  

---

## Usage  
1. Run the main script to start the game:  
    ```bash
    python Main_menu.py
    ```  
2. Choose between **Human vs Human** and **Human vs AI** mode.  
3. Play the game using the GUI.  

---


---

## Conclusion  
This Chess AI project combines advanced algorithms, data structures, and optimization techniques to create an engaging and challenging chess-playing experience. The AI efficiently evaluates board states and makes informed decisions, ensuring smooth gameplay for human players. I hope you enjoy playing and exploring the depths of this project.  
