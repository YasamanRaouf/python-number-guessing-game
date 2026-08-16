# Python Number Guessing Game

A command-line number guessing game built with Python, featuring input validation, hints, and a scoring system.

The game generates a random number between 1 and 100 and challenges the player to guess it. After each incorrect guess, the player receives a hint indicating whether the target number is higher or lower than the player's guess, while the score decreases with each unsuccessful attempt.

## Features

* Random number generation between 1 and 100
* Interactive command-line gameplay
* Input validation and error handling
* Higher/lower hints after incorrect guesses
* Score tracking
* Two implementations with different approaches to project organization

## Implementations

This repository contains two implementations of the same game. The first focuses on simplicity, while the second uses a more modular project structure.

### Solution A — Simple Structure

A straightforward implementation that keeps the project structure minimal and focuses on the core game logic.

**Highlights:**

* Simple and easy-to-follow structure
* Core functionality implemented in a single module
* Minimal setup and dependencies

### Solution B — Modular Structure

A more organized implementation using the `src` pattern, with the application divided into separate modules based on their responsibilities.

**Highlights:**

* Source code organized inside the `src` directory
* Separation of game logic and utility functions
* Dedicated modules for number generation, hints, scoring, and input validation
* Includes project documentation and dependency management
* Easier to maintain and extend

#### Solution B Structure

```text
solution-b/
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

## Concepts & Skills

* Functions and modular programming
* Python modules and packages
* Random number generation
* User input validation
* Exception handling
* Conditional logic
* Score management
* Separation of responsibilities
* Python project organization
* `src`-based project structure

## Getting Started

Clone the repository:

```bash
git clone https://github.com/YasamanRaouf/python-number-guessing-game.git
cd python-number-guessing-game
```

### Solution A

Run the simple implementation:

```bash
python solution-a/number_guesser.py
```

### Solution B

Navigate to the Solution B directory:

```bash
cd solution-b
```

Set the Python path:

```bash
export PYTHONPATH=$PYTHONPATH:$(pwd)
```

Run the game:

```bash
python src/main.py
```

For additional details about the modular implementation, see the [Solution B README](./solution-b/README.md).

## Project Goals

This project explores two different approaches to organizing a small Python application. Solution A focuses on simplicity and direct implementation, while Solution B demonstrates a more modular structure with separation of responsibilities.

Comparing the two implementations provides an opportunity to see how project structure can evolve as an application becomes more organized and maintainable.
