# Tic-Tac-Toe Game in C++

This is a simple implementation of the classic game Tic-Tac-Toe in C++. The game allows two players to take turns marking spaces on a 3x3 grid with their respective symbols (usually 'X' and 'O') with the goal of getting three of their symbols in a row, either horizontally, vertically, or diagonally. This README provides an overview of the game, how to compile and run it, and the rules of the game.

## Table of Contents

- [Game Overview](#game-overview)
- [Prerequisites](#prerequisites)
- [How to Compile](#how-to-compile)
- [How to Play](#how-to-play)
- [Game Rules](#game-rules)
- [Contributing](#contributing)
- [License](#license)

## Game Overview

This C++ Tic-Tac-Toe game is a console-based application that allows two players to play the game by taking turns. It displays the current state of the board after each move and declares a winner or a draw when the game ends.

## Prerequisites

Before you begin, ensure you have the following:

- A C++ compiler installed on your system (e.g., g++, Visual C++).
- A terminal or command prompt for running the compiled program.

## How to Compile

1. Clone this repository to your local machine or download the source code.

2. Open your terminal or command prompt and navigate to the directory where you saved the source code.

3. Compile the code using your C++ compiler. For example, with g++, you can use the following command:

   ```bash
   g++ tic_tac_toe.cpp -o tic_tac_toe
   ```

   This command compiles the `tic_tac_toe.cpp` source file and generates an executable named `tic_tac_toe`.

## How to Play

1. Run the compiled program:

   ```bash
   ./tic_tac_toe
   ```

2. The game will display an empty Tic-Tac-Toe board and prompt the first player (usually 'X') to make a move. Players take turns entering their moves by specifying the row and column where they want to place their symbol.

3. Enter your moves by providing the row and column (e.g., "1 2" for the first row and second column).

4. The game will update the board after each move and continue until a player wins or the game ends in a draw.

5. If a player wins, the game will display the winning player ('X' or 'O'). If the game ends in a draw, it will declare a tie.

6. To play another round, simply run the program again.

## Game Rules

- The game is played on a 3x3 grid.
- Two players take turns, with one using 'X' and the other using 'O'.
- Players cannot place their symbol on a square that is already occupied.
- The game ends when one player gets three of their symbols in a row (horizontally, vertically, or diagonally) or when all squares are filled, resulting in a draw.

## Contributing

Contributions to this simple Tic-Tac-Toe game implementation are welcome. If you have ideas for improvements or new features, please feel free to open an issue or submit a pull request.

## License

This Tic-Tac-Toe game is open-source software released under the [MIT License](LICENSE). You are free to use and modify it as needed for your projects.
