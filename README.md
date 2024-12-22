Chess Project
Overview
This project is a Chess AI game developed in Python, integrating advanced algorithms and data structures to create an intelligent and challenging opponent for human players. The game supports both Human vs Human and Human vs AI modes, providing a comprehensive chess playing experience.
Features
•	Human vs Human mode
•	Human vs AI mode with a challenging AI opponent
•	Move validation and enforcement of chess rules
•	Special moves support: castling, en passant, and pawn promotion
•	Check and checkmate detection
•	Move history and undo functionality
•	GUI developed using Pygame for an interactive experience
Data Structures and Algorithms
Data Structures
•	Dictionary: Stores the current state of each position on the chessboard for efficient access and updates.
•	List: Tracks legal moves, captured pieces, and move history.
•	Stack: Manages move history to facilitate undo operations.
•	Queue: Handles events and actions in a first-in, first-out (FIFO) order.
•	Tree: Utilized in the minimax algorithm to explore possible game states and moves.
•	Tuple: Captures and stores the state of moves, ensuring immutability.
•	Graph: Represents the chessboard and piece movements.
Algorithms
•	Minimax Algorithm with Alpha-Beta Pruning:
o	Time Complexity: O(b^d), where b is the branching factor and d is the depth of the search tree.
o	Space Complexity: O(bd), for storing the game tree and recursive call stack.
•	BFS/DFS: For the movement of the chess pieces like queen,rook,bishop.
Optimization Techniques
•	Alpha-Beta Pruning: Enhances the minimax algorithm by pruning branches that do not affect the final decision, optimizing performance.
•	Move Ordering: Prioritizes capturing moves and checks to increase the efficiency of alpha-beta pruning.
•	State Restoration: Uses tuples to store and restore board states efficiently during move simulations.
Performance Analysis
•	The chess AI efficiently evaluates board states and makes informed decisions, providing a challenging opponent for human players.
•	Optimized algorithms ensure quick response times and smooth gameplay.
Setting up the Environment:
Install Python:
•	Download and install Python 3.8 or later from the official Python website.
•	During installation, make sure to check the option “Add Python to PATH” to make Python accessible from the command line.
Install Required Libraries:
•	Open a terminal or command prompt and run the following command to install the pygame library: pip install pygame.
•	The sys library is part of Python's standard library and is included by default, so you don't need to install it separately.
Troubleshoot Installation Issues:
•	If you face issues, ensure Python is added to your system’s PATH. To check, type python --version in the terminal. If it doesn’t show the version, reinstall Python and check the “Add to PATH” option during setup.
•	If pip isn’t recognized, refer to the pip documentation for help.

Usage
1.	Run the main script to start the game:
Main_menu.py
2.	Choose between Human vs Human and Human vs AI mode.
3.	Play the game using the GUI.
