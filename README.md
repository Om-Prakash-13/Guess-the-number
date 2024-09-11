# Guess The Number Game

## Overview

This is a simple Java console game where the player has to guess a randomly generated number between 1 and 100. The player has a maximum of 7 chances to guess the number correctly. The game provides hints whether the guessed number is too high or too low and displays how close the guess was.

## Features

- **Guessing Mechanism**: Players guess a number between 1 and 100.
- **Hints**: Provides feedback on whether the guessed number is too high or too low.
- **Score Tracking**: Tracks the player's score based on the number of attempts.
- **High Score**: Records and displays the highest score achieved during the game session.
- **Replay Option**: Allows the player to start a new game or quit.

## Getting Started

1. **Clone the Repository**: Clone this repository to your local machine using:
    ```bash
    git clone https://github.com/yourusername/guess-the-number-game.git
    ```
2. **Compile the Program**: Navigate to the directory containing the `guessTheNumberGame.java` file and compile it using:
    ```bash
    javac guessTheNumberGame.java
    ```
3. **Run the Program**: Execute the compiled Java program using:
    ```bash
    java guessTheNumberGame
    ```

## Gameplay Instructions

1. When prompted, enter `1` to start the game.
2. Guess a number between 1 and 100.
3. Based on the feedback, adjust your guesses. You have a maximum of 7 chances to guess the correct number.
4. After the game ends, you will see your score and the high score.
5. You can choose to play again by entering `1` or quit by entering `-1`.

## Code Explanation

- **`game()` Method**: Handles the game logic, including generating a random number, receiving user input, providing hints, and updating scores.
- **`main(String[] args)` Method**: Manages the game flow, allows the player to start or quit the game.

## Acknowledgements

- Java Programming Language
- Random Number Generation in Java

## Author

- **Om Prakash Adhikari**

Feel free to reach out if you have any questions or suggestions for improvements!
