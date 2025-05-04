# 🌐 A* Maze Algorithm

This project implements the A* (A-star) pathfinding algorithm in a grid-based maze environment.

---

## 🎯 Objective

To find the shortest path from a start point to a goal point in a maze while avoiding obstacles using the A* search algorithm.

---

## 🧠 Algorithm Overview

- Uses **Manhattan distance** as the heuristic
- Prioritizes nodes based on `f(n) = g(n) + h(n)`
  - `g(n)`: cost from start to current node
  - `h(n)`: estimated cost from current to goal (heuristic)
- Explores the most promising paths first
- Visualizes visited nodes, current path, and obstacles

---

## 🖥️ Features

- Maze generation or manual design
- Real-time pathfinding visualization (e.g. with Pygame)
- Handles large grids efficiently
- Color-coded path, obstacles, start, and goal nodes

---

## 🚀 How to Run

```bash
python main.py
```

Dependencies:
- Python 3.x
- `pygame` (if visualization is used)

Install dependencies:
```bash
pip install pygame
```

---

## 📁 File Structure

```
a_star_maze_algorithm/
├── main.py          # Main A* logic and maze controller
└── README.md        # This file
```

---

## 📜 License

Free to use for learning and demonstration purposes.
