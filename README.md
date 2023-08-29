# Rock, Paper, Scissors Game

## Overview

This simple JavaScript project was created with the primary goal of reinforcing fundamental concepts in JavaScript and programming logic. The project implements the classic Rock, Paper, Scissors game, allowing users to play against the computer and determine the winner based on their choices.

## Learning Objectives

The main objectives of this project are:

- Consolidating a foundational understanding of JavaScript.
- Practicing programming logic and decision-making.
- Implementing basic user input validation.
- Demonstrating the use of functions and control flow.

## How to Play

1. Open the JavaScript file (e.g., `game.js`) in your preferred code editor.
2. Run the script using a JavaScript runtime (e.g., Node.js).
3. The game will automatically play one round where the user chooses "rock."
4. The computer's choice and the game's outcome will be displayed in the console.

## Features

- User can choose "rock," "paper," or "scissors."
- Computer makes a random choice.
- Determines the winner based on the classic game rules.
- Special feature: If the user chooses "bomb," they automatically win.

## Code Explanation

- `getUserChoice`: Takes a user input, converts it to lowercase, and validates it. If the input is valid, it's returned; otherwise, an error is logged.

- `getComputerChoice`: Generates a random number between 0 and 2, and maps it to "rock," "paper," or "scissors" using a switch statement.

- `determineWinner`: Compares user and computer choices to determine the winner based on the game rules. Includes a special case for "bomb."

- `playGame`: Automatically plays one round of the game, displaying the computer's choice, the user's choice ("rock"), and the game outcome in the console.

## Special Note

- The game includes a secret "bomb" option that makes the user an instant winner.

This project serves as an excellent exercise for consolidating your understanding of JavaScript fundamentals and honing your programming logic skills. Feel free to modify and enhance the code as you continue your learning journey!

---

Developed by Rodrigo Lima


