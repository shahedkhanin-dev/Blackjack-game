# Blackjack Game

A simple command-line Blackjack game built in Python. The player competes against the computer and tries to get as close to 21 as possible without busting.

## Features

- Random card dealing
- Player vs. computer gameplay
- Hit or stand mechanic
- Ace value adjustment logic
- Replay option after each round
- ASCII title art for a retro terminal feel

## How to Play

1. Open a terminal in the project folder.
2. Run:
   ```bash
   python main.py
   ```
3. The game deals cards to you and the computer.
4. Choose:
   - `y` to hit and draw another card
   - `n` to stand and compare totals
5. Try to beat the dealer without going over 21.

## Rules

- If your hand total is greater than 21, you bust and lose.
- If the computer busts, you win.
- If both hands total the same, the round is a draw.
- If your total is higher than the computer's, you win.
- If the computer's total is higher, you lose.

## Project Structure

```text
Blackjack-game/
├── art.py
├── main.py
├── README.md
```

- `main.py` contains the game logic
- `art.py` contains the ASCII logo shown at startup

## Requirements

- Python 3.x

No external libraries are needed.

## Example

```bash
$ python main.py
```

## Author

This is a beginner-friendly Python mini-project for learning basic game logic, loops, conditionals, and randomization.

---

Enjoy the game!
