# Tic-Tac-Teo-Game-In-C-
A simple 2-player console-based Tic Tac Toe game built using C++. Players take turns placing their marker (X or O) on a 3×3 board until one player wins or the game ends in a tie.


🚀 Features

1. Console-based interactive game

2. Two players can play turn by turn

3. Input validation (avoids invalid or occupied slots)

4. Declares the winner or tie

📂 Project Structure

tic-tac-toe/

│── main.cpp # Source code of the game

│── README.md # Documentation

🕹️ How to Play

1. Run the program.

2. Player 1 chooses their marker (X or O).

3. Players take turns entering the slot number (1–9) to place their marker.

4. The first player to align three markers in a row, column, or diagonal wins.

5. If all slots are filled with no winner, it’s a tie.

🛠️ Compilation & Execution

. Open terminal/command prompt in the project folder and run:

    g++ main.cpp -o tic_tac_toe

    ./tic_tac_toe

    
📸 Example Gameplay

 1 | 2 | 3
---|---|---
 4 | 5 | 6
---|---|---
 7 | 8 | 9

Player 1 choose your marker: X or O
X
its player1's turn Enter your slot: 5

 1 | 2 | 3
---|---|---
 4 | X | 6
---|---|---
 7 | 8 | 9



📌 Future Improvements

🤖 Add single-player mode with computer AI

📝 Implement scoreboard for multiple rounds

🎨 Better UI with colors for X and O
