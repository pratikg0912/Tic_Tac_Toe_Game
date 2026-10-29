# Tic-Tac-Toe Game

A single-file browser game where the player plays against the computer in a classic Tic-Tac-Toe match.

## Features

- 3x3 game board
- Human vs computer gameplay
- Smart move selection using minimax logic
- Score tracking for wins, losses, and draws
- Reset board button
- Responsive layout for desktop and mobile
- Works directly in the browser without any dependencies

## How to Play

1. Open `tic-tac-toe.html` in a browser
2. Click any empty square to place your X
3. The computer will automatically play O after your move
4. The game announces the winner or a draw
5. Use the reset button to start a new round

## Project Structure

- `tic-tac-toe.html` — complete game logic and interface
- `PRD_tic_tac_toe.md` — product requirements for this game
- `README.md` — project overview and setup instructions

## Run Locally

Open `tic-tac-toe.html` directly in a browser, or serve the folder with a local web server:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000/tic-tac-toe.html
```

## Technical Details

- Built with plain HTML, CSS, and JavaScript
- Single-file game implementation
- No external libraries required
- Computer logic uses a minimax-based decision algorithm
- Scoreboard persists during the current session

## License

This project is intended for personal or educational use.
