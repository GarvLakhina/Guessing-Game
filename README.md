# Guessing Game in Rust

A simple number guessing game implemented in Rust, where the player tries to guess a randomly generated number between 1 and 100.

## Features

- Generates a random number between 1-100
- Provides feedback on each guess (too high/too low)
- Tracks the number of attempts
- Input validation to ensure only valid numbers are accepted
- Clear instructions and user-friendly interface

## Prerequisites

- [Rust](https://www.rust-lang.org/tools/install) (version 1.60 or later recommended)
- Cargo (comes with Rust installation)

## Installation

1. Clone the repository or download the source code
2. Navigate to the project directory in your terminal

## How to Play

1. Run the game using:
   ```bash
   cargo run
   ```
2. Enter your guess when prompted
3. The game will tell you if your guess is too high or too low
4. Keep guessing until you find the correct number
5. The game will show you how many attempts it took to guess correctly

## Example Gameplay

```
Welcome to the Guessing Game!
I'm thinking of a number between 1 and 100.

Enter your guess:
50
You guessed: 50
Too small!

Enter your guess:
75
You guessed: 75
Too big!

Enter your guess:
63
You guessed: 63

🎉 Congratulations! You win!
It took you 3 attempts.
```

## Project Structure

- `src/main.rs` - Contains the main game logic
- `Cargo.toml` - Project configuration and dependencies

## Building the Project

To build the project in release mode:

```bash
cargo build --release
```

The executable will be available at `target/release/guessing_game.exe` (Windows) or `target/release/guessing_game` (Unix-like systems).

## License

This project is open source and available under the [MIT License](LICENSE).