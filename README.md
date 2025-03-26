# Flappy Dragon

Flappy Dragon is a simple terminal-based game built using the `bracket-lib` Rust library. This game mimics the mechanics of "Flappy Bird," where the player controls a character that must avoid obstacles by flapping to stay airborne.

## Features
- Simple gravity-based movement
- Basic game loop with menu, playing, and game over states
- Controls using the keyboard
- Built with Rust and `bracket-lib`

## Installation
### Prerequisites
- Rust installed on your system. You can install Rust using [rustup](https://rustup.rs/).

### Steps
1. Clone this repository:
   ```sh
   git clone <repository-url>
   cd flappy-dragon
   ```
2. Install dependencies:
   ```sh
   cargo build
   ```
3. Run the game:
   ```sh
   cargo run
   ```

## Controls
- `P` - Start the game
- `Spacebar` - Flap (jump)
- `Q` - Quit the game

## How It Works
- The player (represented by `@`) moves forward automatically.
- Gravity pulls the player downward unless they flap.
- The game ends when the player hits the bottom of the screen.
- The game starts in the main menu, where you can choose to play or quit.
- After losing, you can restart or exit.

## Game Modes
- **Menu**: The starting screen where players can begin the game.
- **Playing**: The game is in progress, and the player must flap to stay in the air.
- **Game Over**: The player has lost and can restart or quit.

## Dependencies
- [bracket-lib](https://crates.io/crates/bracket-lib): A Rust game development library for building roguelikes and terminal-based games.

## Future Improvements
- Adding obstacles to increase difficulty
- Implementing a scoring system
- Adding sound effects
