Fantasy Land RPG

Introduction
  Fantasy Land RPG is a turn-based role-playing game developed using Python and the Pygame library. In this game, the player controls a knight character who battles multiple enemies and a final boss using strategic combat mechanics. The gameplay focuses on turn-based decision making, health management, and limited healing resources. The project is designed to demonstrate core game development concepts such as combat logic, modular programming, visual rendering, and game state persistence. This RPG was created as an academic project to showcase practical implementation of programming and game design principles.

---

Tech Stack
Programming Language: Python 3.11
Game Framework: Pygame
Data Storage: JSON
IDE / Editor:** Visual Studio Code
Platform: Windows

---

Libraries Used
pygame – Used for game window creation, graphics rendering, event handling, and animations
json – Used to save and load game progress
os – Used for file and directory handling
* **random** – Used for damage calculation and boss special attack logic

---

## 📂 Project Structure

```
Fantasy_Land_RPG/
│
├── assets/
│   └── images/
│       └── characters/
│           ├── knight.png
│           ├── bandit.png
│           └── boss.png
│
├── data/
│   └── game_save.json
│
├── game/
│   ├── characters.py
│   ├── combat.py
│   └── save_load.py
│
├── main.py
├── README.md
└── requirements.txt
```

---

## 📄 File Descriptions

### `main.py`

This is the main entry point of the game. It controls the game loop, user input, rendering of characters and UI elements, and integrates combat logic with visuals. It also manages player actions such as attack, heal, restart, and save/load functionality.

### `game/characters.py`

This file defines the character structure used in the game. It includes attributes such as character name, current health, and maximum health for both the player and enemies.

### `game/combat.py`

This file handles all combat-related logic. It manages turn-based combat flow, damage calculation, enemy progression, boss special attack logic, and win or game-over conditions.

### `game/save_load.py`

This file is responsible for saving and loading the game state. It stores player health, enemy health, current enemy index, and potion count in a JSON file, allowing the game to resume from the previous state.

### `assets/images/characters/`

This folder contains all character sprite images used in the game, including the knight, enemies, and boss.

### `data/game_save.json`

This file stores saved game data. It is automatically created and updated during gameplay.

---

## ▶️ How to Run the Game

1. Install Python 3.11
2. Install Pygame:

   ```bash
   pip install pygame
   ```
3. Run the game:

   ```bash
   python main.py
   ```

---

## 🎯 Features Implemented

* Turn-based combat system
* Player attack and heal actions
* Limited healing resources
* Multiple enemies and boss fight
* Boss special attack
* Visual character sprites and health bars
* Save and load game progress
* Restart option

