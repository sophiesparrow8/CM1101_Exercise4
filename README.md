# CM1101 Exercise 4

This repository contains my solution for **Exercise 4** for the CM1101 module.

## Features Implemented

- `map.py` contains a dictionary of rooms with **name**, **description**, and **exit mappings**
- `game.py` implements:
  - Display of current room
  - Menu of available exits
  - Input loop that **rejects invalid commands**
  - **Input normalisation** (strips punctuation and handles mixed case)
  - Movement between rooms
- All **24 doctests pass** without modification

---

## ▶ Running the Game

```bash
python3 game.py
