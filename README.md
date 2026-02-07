# Checkers Game (Python)

A Python implementation of the classic Checkers board game featuring rule validation, piece movement, and turn-based gameplay. The project focuses on modeling game mechanics using clean object-oriented design.

## Features

* Standard 8×8 Checkers board logic
* Legal move validation
* Capture mechanics
* Turn management for two players
* Win and draw detection

## Architecture

The game is structured around core components:

* **Soldier** — represents individual pieces and movement rules
* **Player** — manages each player's pieces
* **Manager** — controls game flow and rule enforcement

This separation keeps game logic modular and easy to extend.

## Requirements

* Python 3.x
* `termcolor` library

Install dependency:

```
pip install termcolor
```

## Running

```
python checkers.py
```

## Purpose

This project demonstrates object-oriented design, board state management, and rule-driven gameplay implementation in Python.

---

A lightweight implementation focused on clarity, structure, and game logic fundamentals.

