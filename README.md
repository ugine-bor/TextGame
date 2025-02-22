# Argument Simulator: Philosophical Debates
# Recreation of a text game found in "Talos Principle" using python 

![GitHub last commit](https://img.shields.io/github/last-commit/ugine-bor/argument-simulator)

## Features

- **Text-based RPG mechanics** with multiple dialogue paths
- **Branching narratives** that change based on your choices
- **Hidden options** unlocked through repeated playthroughs
- **Keyboard-controlled interface** with number-based selection
- **Atmospheric typewriter effect** for dramatic delivery
- **4+ philosophical debate strategies** to master:
  - "Это так!" (This is so!)
  - "Это не так!" (This is not so!)
  - "Это ошибка!" (This is a mistake!)
  - ...and more!

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ugine-bor/TextGame.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Start:
   ```bash
   python main.py
   ```

## 🎯 How to Play

```text
1. Choose your character:
   - Голдбум (Goldboom)
   - Сократ (Socrates)
   - Помощник библиотекаря (Librarian's Assistant)

2. Engage in dialectical combat using:
   1-9 keys to select arguments

3. Discover dialogue options by:
   - Repeating debate loops
   - Challening opponents' epistemological foundations
```

## Project Structure

```text
├── engine.py        # Core game logic and state machine
├── main.py          # Entry point
├── requirements.txt # requirements
└── states.json      # All dialogue branches and game flow
```

### Engine Highlights
- **State Machine Architecture** for seamless scene transitions
- **Dynamic Answer Selection** with random response variations
- **Loop Counter System** unlocks dialogue options

---
*"Будет здорово, если мы начнем понимать друг друга."*
```
