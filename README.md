# Fusion Grid

## Overview
**Fusion Grid** is a hybrid online board game that combines the rules of Chess and Connect4. This unique game, pits one player using Connect4 rules against another using Chess rules.

## Rules
### Objective:
- **Connect4 Player**: Win by connecting 4 pieces in a straight line (horizontal, vertical, or diagonal).
- **Chess Player**: Win by preventing the Connect4 player from forming a straight line with 4 pieces.

### Game Play:
- **Connect4 Player**:
  - Has 15 pieces.
  - Places pieces at one end of the board, which fall to the other side as if the board were vertical.
  - Pieces must go as far down as possible.
- **Chess Player**:
  - Moves pieces in the usual manner.
  - Aims to block the Connect4 player from connecting 4 pieces in a line.

### Maximum Moves:
- Minimum of 4 moves (if Connect4 player wins without interruption).
- Maximum of 15 moves (if Chess player successfully defends every move).

### Scoring:
- **Chess Player**:
  - Earns 10 points for each defended move after move 4.
- **Connect4 Player**:
  - Earns 10 points for each saved move out of 15 moves.
  - Secures 150 points for a win.

### Rounds:
- The game was played in Technothlon'23 Round 2, Junior Section.
  
## Tech Stack
- **Backend**: Django
- **Frontend**: ReactJS

## Contact
For any questions or feedback, please contact saumya10e9@gmail.com

