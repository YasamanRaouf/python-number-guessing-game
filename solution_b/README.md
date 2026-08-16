# Number Guesser Game — Solution B

## Overview

A modular implementation of the Number Guesser Game built with Python.

The game generates a random number between 1 and 100 and challenges the player to guess it. After each incorrect guess, the player receives a hint indicating whether the target number is higher or lower than their guess, while the score decreases with each unsuccessful attempt.

## Project Structure

This implementation follows a modular structure using the `src` pattern, with different parts of the application separated based on their responsibilities.

```text
solution_b/
├── src/
│   ├── main.py
│   ├── game_logic/
│   │   ├── __init__.py
│   │   ├── number_generator.py
│   │   ├── hint_generator.py
│   │   └── scorer.py
│   └── utils/
│       ├── __init__.py
│       └── input_validator.py
├── README.md
└── requirements.txt
```

## How to Run

From the repository root, navigate to the project directory:

```bash
cd solution_b
```

Add the project directory to `PYTHONPATH`:

```bash
export PYTHONPATH=$PYTHONPATH:$(pwd)
```

Run the game:

```bash
python src/main.py
```

Follow the on-screen prompts to play the game.

## Modules

### `src/main.py`

The main entry point of the application. It handles the game loop, user interaction, and display of game messages.

### `src/game_logic/`

Contains the core game logic:

* **`number_generator.py`** — Generates the target random number.
* **`hint_generator.py`** — Provides hints based on the player's guess.
* **`scorer.py`** — Manages the scoring system.

### `src/utils/`

Contains utility functions:

* **`input_validator.py`** — Validates user input.
