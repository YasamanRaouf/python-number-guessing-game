# Python Number Guessing Game

A command-line number guessing game built with Python, featuring input validation, hints, and a scoring system.

The game generates a random number within a specified range and challenges the player to guess it. After each incorrect guess, the player receives a hint indicating whether the target number is higher or lower, while the score decreases with each unsuccessful attempt.

## Features

* Random number generation within a specified range
* Interactive command-line gameplay
* Input validation and error handling
* Higher/lower hints after incorrect guesses
* Score tracking
* Option to quit the game
* Two different implementations with different project structures

## Project Structure

This repository contains two implementations of the same game, exploring different approaches to organizing a small Python application.

### Solution A — Simple Structure

A straightforward implementation that keeps the project structure minimal and focuses on the core game logic.

**Highlights:**

* Simple and easy-to-follow structure
* All core functionality in a single module
* Suitable for a small command-line application

### Solution B — Modular Structure

A more structured implementation using the `src` pattern, with the application logic separated into different modules.

**Highlights:**

* Source code organized inside the `src` directory
* Separation of different responsibilities into modules
* Includes project-specific documentation and dependency management
* More scalable structure for extending the application

## Concepts & Skills

* Functions and modular programming
* Random number generation
* User input and validation
* Exception handling
* Conditional logic
* Score management
* Python project organization

## Getting Started

Clone the repository:

```bash
git clone 
cd python-number-guessing-game
```

Choose either implementation and follow its corresponding instructions.

### Solution A

```bash
python solution-a/number_guesser.py
```

### Solution B

See the [Solution B README](./solution-b/README.md) for setup and execution instructions.

## Project Goals

This project explores how the same functionality can be implemented using different levels of code organization, from a simple single-module structure to a more modular `src`-based structure.
