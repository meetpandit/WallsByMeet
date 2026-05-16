# 🧱 WallsByMeet

> A modern online multiplayer strategy game — built by **[@li_meet_less__](https://www.instagram.com/li_meet_less__)**

[![Play Now](https://img.shields.io/badge/▶%20Play%20Now-Live%20Demo-7c3aed?style=for-the-badge)](https://meetpandit.github.io/WallsByMeet)
[![Made by Meet](https://img.shields.io/badge/Made%20by-Meet-f472b6?style=for-the-badge)](https://www.instagram.com/li_meet_less__)
[![License: MIT](https://img.shields.io/badge/License-MIT-60a5fa?style=for-the-badge)](LICENSE)

---

## 🎮 What is WallsByMeet?

**WallsByMeet** is a modern browser-based remake of the classic board game **Quoridor** — a brilliant strategy game where two players race to reach the opposite side of the board while placing walls to block each other's path.

Pure strategy. No luck. Just walls and wits.

---

## ✨ Features

- 🎮 **Local Hotseat** — two players on the same device
- 🤖 **AI Opponent** — three difficulty levels (Easy, Medium, Hard)
- 🌐 **Online Multiplayer** — play with friends via a room code or get matched randomly
- ♟️ **Jump moves** — leap over adjacent pawns
- 🔒 **Path validation** — walls can never fully trap a player (BFS enforced)
- ↩️ **Undo** — take back your last move (local & AI modes)
- 🎨 **Modern dark UI** — smooth animations and visual feedback

---

## 🕹️ How to Play

### 🎯 Objective
Be the first player to reach the **opposite side** of the board.
- **Player 1 (Pink)** starts at the top and must reach **row 9 (bottom)**
- **Player 2 (Blue)** starts at the bottom and must reach **row 1 (top)**

---

### 🔄 On Your Turn
Each turn you must do **one** of the following:

#### 1. 🚶 Move Your Pawn
- Select **Move mode** (left panel)
- Valid moves are **highlighted in purple**
- Click any highlighted cell to move
- You can move **up, down, left, or right** (1 step)

#### 2. 🧱 Place a Wall
- Select **Wall mode** (left panel)
- Hover over the board — walls **preview in green** (valid) or **red** (invalid)
- Click to place a 2-cell wall (horizontal or vertical)
- Each player has **10 walls** total — use them wisely!

---

### 🦘 Jump Rules
If your opponent's pawn is **directly adjacent**, you can **jump over them**:
- If the space behind them is free → jump straight over
- If blocked by a wall or edge → jump **sideways** instead

---

### 🧱 Wall Rules
- Walls span **2 cells** and block movement between them
- Walls **cannot overlap** or cross each other
- You **cannot place a wall** that completely traps either player (no path to goal = invalid)
- Once placed, walls **cannot be moved**

---

### 🏆 Winning
First player to step onto any cell of the **opposite end row** wins!

---

## 🌐 Online Multiplayer

### Create a Room
1. Select **Online** from the menu
2. Click **Create Room**
3. Share the **6-character room code** with your friend
4. Wait for them to join — game starts automatically!

### Join a Room
1. Select **Online** from the menu
2. Click **Join Room**
3. Enter the **room code** your friend shared
4. Click **Join** — you're in!

### Random Match
1. Select **Online** from the menu
2. Click **🎲 Random Match**
3. You'll be matched with another player automatically

---

## 🤖 AI Difficulty Guide

| Level | Behavior |
|-------|----------|
| 😊 Easy | Makes random legal moves, occasionally places walls |
| 🧠 Medium | Follows shortest path, tries to block you with walls |
| 💀 Hard | Uses minimax strategy, optimal wall placement & racing |

---

## 🚀 Getting Started (Self-Host)

```bash
git clone https://github.com/meetpandit/WallsByMeet.git
cd WallsByMeet
# Just open index.html in your browser — no build step needed!
open index.html
```

Or deploy instantly with **GitHub Pages**:
1. Fork this repo
2. Go to **Settings → Pages → Branch: main → Save**
3. Visit `https://meetpandit.github.io/WallsByMeet`

---

## 🛠️ Built With

- **Vanilla HTML, CSS & JavaScript** — zero dependencies
- **Firebase Realtime Database** — online multiplayer sync
- **BFS Pathfinding** — wall validation
- **Minimax Algorithm** — Hard AI opponent

---

## 📸 Follow the Creator

Made with ❤️ by **Meet** — follow on Instagram for more projects:

[![Instagram](https://img.shields.io/badge/@li__meet__less__-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/li_meet_less__)

---

## 📄 License

MIT License — free to use, modify, and share. Credit appreciated! 🙏
