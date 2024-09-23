# Mastermind-game
Mastermind is a code-breaking game where the player must guess a secret code made up of colored pegs. This implementation is a text-based version of the classic game, written in Python.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Gameplay](#gameplay)
- [Requirements](#requirements)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Contributing](#contributing)
- [License](#license)

## Overview

This is a Python implementation of the classic Mastermind game. The computer generates a secret code consisting of 4 colored pegs, chosen from a set of 6 colors. The player has 10 attempts to guess the correct code. After each guess, the game provides feedback on how many colors are in the correct position and how many are correct but in the wrong position.

## Features

- Randomly generated secret code
- 6 available colors: Red (R), Green (G), Blue (B), Yellow (Y), White (W), Orange (O)
- Input validation for player guesses
- Feedback after each guess on:
  - Correct colors in the correct position
  - Correct colors in the wrong position
- Limited number of attempts (10 tries)
  
## Gameplay

1. The computer generates a secret code consisting of 4 random colors from a set of 6.
2. The player enters their guess by inputting 4 colors.
3. After each guess, feedback is provided:
   - Number of colors that are in the correct position.
   - Number of correct colors but in the wrong position.
4. The player wins if they guess the code correctly within 10 attempts.
5. If all attempts are exhausted without a correct guess, the game reveals the secret code.

## Requirements

- Python 3.x
- No external libraries required.

## Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/mastermind-game.git
    cd mastermind-game
    ```

2. Run the game:

    ```bash
    python mastermind.py
    ```

## How to Play

1. When prompted, enter a guess by typing four color initials separated by spaces (e.g., `R G B Y`).
2. The game will provide feedback on your guess:
   - **Correct positions**: Number of colors in the correct position.
   - **Incorrect positions**: Number of correct colors in the wrong position.
3. Keep guessing until you crack the code or run out of attempts.
4. After the game ends, the secret code will be revealed if you didn’t guess it correctly.

## Contributing

If you'd like to contribute to this project, feel free to submit a pull request or open an issue for bugs, suggestions, or enhancements.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a pull request

## License

This project is licensed under the MIT License.
