# Mastermind Game

This is a Python implementation of the classic Mastermind game. The goal of the game is to guess a 4-digit secret code within a limited number of turns.

## Instructions

1. Run the `mastermind.py` script to start the game.
2. You will have 12 turns to guess the secret code.
3. Input a 4-digit code where each digit is in the range 1 to 8.
4. After each guess, the game will provide feedback on the correctness of your guess.
5. The feedback includes the number of correct digits in the correct position and the number of correct digits in the wrong position.
6. Keep guessing until you either solve the code or run out of turns.

## Functions

- `create_code()`: Generates a random 4-digit code using digits from 1 to 8.
- `show_instructions()`: Displays the game instructions to the user.
- `show_results(correct_digits_and_position, correct_digits_only)`: Shows the results of each turn to the user.
- `user_input()`: Takes user input for guessing the code and validates it.
- `take_turn(code)`: Handles the logic for each turn, including user input, validation, and result calculation.
- `show_code(code)`: Displays the secret code after the game ends.
- `check_correctness(turns, correct_digits_and_position)`: Checks if the user has guessed the correct code and provides feedback.
- `run_game()`: Main function to run the game, including initialization, game loop, and ending.

## Dependencies

This game relies on the `random` module for generating random numbers.

## How to Run

Simply execute the `mastermind.py` script in a Python environment to start the game.

```bash
python mastermind.py
