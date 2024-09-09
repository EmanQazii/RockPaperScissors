# Rock Paper Scissors Game

This is a simple command-line Rock-Paper-Scissors game built using C++. The game allows you to play multiple rounds against the computer and keeps track of the scores for both the player and the computer. It also includes ASCII art to display your choices and basic game instructions.

## Features

- Play multiple rounds of Rock-Paper-Scissors.
- See the round number, user and computer choices, and the winner of each round.
- Scoreboard to track the player's and computer's scores.
- ASCII representation of Rock, Paper, and Scissors.
- Input validation to ensure valid choices are entered.
- Menu options to start a new game, view the scoreboard, or exit.

## How to Play

1. **Start the game**:
   The main menu will give you the option to:
   - Press `1` to start the game.
   - Press `2` to view the scoreboard.
   - Press `0` to exit the game.

2. **Choose Rock, Paper, or Scissors**:
   When the game starts, you will be prompted to enter your choice:
   - Enter `r` for **Rock**.
   - Enter `p` for **Paper**.
   - Enter `s` for **Scissors**.
   - Enter `x` to exit the game and return to the main menu.

3. **Winning Conditions**:
   - Rock beats Scissors.
   - Paper beats Rock.
   - Scissors beats Paper.
   If both the player and the computer choose the same item, it's a tie.

4. **Play Again**:
   After each round, you will have the option to play again or return to the main menu.

## Game Rules

- **Player wins**: Player's score is incremented by 5.
- **Computer wins**: Computer's score is incremented by 5.
- If the player loses, their score decreases by 1 (but can't go below 0).
- If the computer loses, its score decreases by 1 (but can't go below 0).
  
## Requirements

- A C++ compiler such as `g++` or MSVC.
- Windows operating system (uses `windows.h` for certain functions like `Sleep` and `system("cls")`).

## How to Compile and Run

### On Linux/macOS

1. Open your terminal and navigate to the directory where the source code is located.
2. Compile the code using `g++`:

    ```bash
    g++ -o rock_paper_scissors rock_paper_scissors.cpp
    ```

3. Run the compiled program:

    ```bash
    ./rock_paper_scissors
    ```

### On Windows

1. Open your command prompt or PowerShell and navigate to the directory where the source code is located.
2. Compile the code using `g++`:

    ```bash
    g++ -o rock_paper_scissors rock_paper_scissors.cpp
    ```

3. Run the compiled program:

    ```bash
    rock_paper_scissors.exe
    ```



Computer Score  : 5
-----------------------------------------------------------------------------------------------------------------------

DO YOU WANT TO PLAY AGAIN(y/n)? 
