Tic-Tac-Toe Game
This is a simple command-line Tic-Tac-Toe game implemented in C++. The game allows two players to take turns marking the spaces in a 3x3 grid with 'X' and 'O'. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row wins the game.

Features
Two-player game
Command-line interface
Simple game logic
Input validation to ensure valid moves
Getting Started
Prerequisites
C++ compiler (e.g., g++)
Installing
Clone the repository:
bash
git clone https://github.com/yourusername/tic-tac-toe-cpp.git
cd tic-tac-toe-cpp
Compile the program:

bash
g++ -o tic_tac_toe main.cpp
Run the executable:

bash
./tic_tac_toe
How to Play
Player one chooses their marker (either 'X' or 'O').
Players take turns to enter the row and column number (0, 1, or 2) to place their marker.
The game checks for a winner after each move.
The game ends when there is a winner or all spaces are filled (a tie).
Example
sql
Player one, choose your marker: X
  0 1 2
0  | | 
  -----
1  | | 
  -----
2  | | 
It's player 1's turn. Enter your move (row and column): 0 0
  0 1 2
0 X| | 
  -----
1  | | 
  -----
2  | | 
It's player 2's turn. Enter your move (row and column): 1 1
  0 1 2
0 X| | 
  -----
1  |O| 
  -----
2  | | 
License
This project is licensed under the MIT License - see the LICENSE file for details.


