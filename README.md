# Tic-Tac-Toe Game with AI

This repository contains a Python implementation of the classic Tic-Tac-Toe game with an AI opponent. You can play against the AI or with another player in a player-versus-player (PvP) mode.

## Features

- Play Tic-Tac-Toe against an AI opponent.
- Switch between different AI difficulty levels.
- Customizable game board and UI settings.
- Reset the game at any time.
- Player-versus-player (PvP) mode available.

## Getting Started

To run the game, you need to have Python and Pygame installed. You can install Pygame and other dependencies using the provided `requirements.txt` file:

```bash
pip install -r requirements.txt
```
Once you have the required dependencies, run the game using the following command:

```bash
python Tictactoe.py
```

## Game Controls
- Click on an empty square to make your move.
- Press "G" to toggle between AI and PvP modes.
- Press "1" to set the AI difficulty to level 1.
- Press "0" to set the AI difficulty to level 0 (easier).
- Press "R" to reset the game at any time.

## Configuration
You can customize various aspects of the game by editing the `config.ini` file. This includes adjusting the game window's dimensions, colors, and UI settings.

## AI Implementation
The AI for Tic-Tac-Toe is implemented using minimax and alpha-beta pruning algorithms. The AI evaluates the best move based on the current game state and difficulty level.

## License
This code is provided under the MIT License. Feel free to use, modify, and share it as needed.

## Code Files
### `ai.py`
Contains the AI class that implements the Tic-Tac-Toe AI using minimax and alpha-beta pruning algorithms.

### `config.ini`
Configuration settings for the game's user interface and colors.
 
### `requirements.txt`
Lists the Python dependencies required to run the game.

### `tictactoe.py`
The main Python file that implements the game logic, user interface, and gameplay.

