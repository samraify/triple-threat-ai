# 🎮 Triple Threat: Tic Tac Toe

An advanced AI-powered version of Tic Tac Toe featuring layered boards, bonus turns, and strategic gameplay. This project incorporates the **Minimax algorithm with Alpha-Beta pruning** and a custom heuristic to challenge human players on a dynamic 3x3x3 board system.

---

## 📽️ Demo Video

[Download Gameplay Demo](https://github.com/samraify/triple-threat-ai/raw/refs/heads/main/k224585%20ai%20demo%20video.mp4) 
This video is part of the repo so in order to view it please click on the URL and download.

---

## 📌 Table of Contents

- [Project Overview](#project-overview)
- [Game Rules](#game-rules)
- [AI Design](#ai-design)
- [Game Mechanics](#game-mechanics)
- [Installation](#installation)
- [Group Members](#-group-members)

---

## 🚀 Project Overview

**Triple Threat: Tic Tac Toe** enhances the original Tic Tac Toe experience by introducing:
- A 3x3 grid of smaller 3x3 mini boards.
- Strategic depth via layered win conditions.
- A challenging AI opponent powered by the Minimax algorithm with Alpha-Beta pruning.
- A custom heuristic evaluation guiding AI decisions based on control, threats, and board dominance.

The aim of this project is to explore AI decision-making in a more complex game environment and provide engaging gameplay for human players.

---

## 🎯 Game Rules

### Original Rules
- Two players alternate placing X or O on a 3x3 grid.
- First to align 3 symbols horizontally, vertically, or diagonally wins.
- A draw occurs if all cells are filled without a winner.

### Modifications in Triple Threat:
- The main board is a 3x3 grid of mini Tic Tac Toe boards.
- Winning a mini board captures that cell on the main board.
- Winning three mini boards in a row (horizontal/vertical/diagonal) wins the game.
- Winning a mini board allows the player to play another turn.
- Drawn mini boards remain neutral.
- The player must play in the mini board that corresponds to the opponent's last move—unless it's completed, in which case any board is valid.

---

## 🧠 AI Design

### Algorithm:
- **Minimax Algorithm** with **Alpha-Beta Pruning** to reduce unnecessary evaluations and improve response time.

### Heuristic Evaluation:
- **+100/-100** for winning/losing a mini board.
- **+10/-10** for forming 2-in-a-row patterns in mini boards.
- **+300/-300** for near-wins on the main board.
- **Bonus** for controlling center positions (both mini and main board).
- These weights guide the AI’s choices by evaluating the most advantageous move based on board status.

---

## ⚙️ Game Mechanics

- **Main Board**: 3x3 grid of mini boards.
- **Mini Board Win**: Captures the respective cell on the main board.
- **Bonus Turn**: Awarded on winning a mini board.
- **Win Condition**: Control three mini boards in a line.
- **Draw**: All boards are complete without a winning line.

---

## 🛠️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/triple-threat-tic-tac-toe.git
   cd triple-threat-tic-tac-toe

2. **Install dependencies:**
   ```bash
   pip install numpy
   pip install tkinter

3. **Run the game:**
   ```bash
   python main.py


## 🧑‍💻 Group Members

- **Samra Shahid** — *22K-4585*

