# Rock Paper Scissors Game

## Overview
This project is a Rock, Paper, Scissors game where your program must play against four different bots and win at least 60% of the matches. Your task is to implement a strategy in `RPS.py` that adapts to different opponents.

## Challenge Description
A program that selects moves at random will typically win 50% of the time. To pass this challenge, your program must analyze the opponent’s patterns and implement a winning strategy.

## How It Works
- You will modify the `player` function in `RPS.py`.
- The function takes the opponent's last move as input and returns your next move.
- Your function must remember past plays to adapt its strategy.
- The first move will receive an empty string as input.

## Development Guidelines
- **Do not modify** `RPS_game.py`.  
- Write all your logic in `RPS.py`.  
- Use `main.py` to test your implementation.

## Running the Game
To play a match between your `player` function and a bot, use:

```python
play(player, bot_name, num_games, verbose=True)
