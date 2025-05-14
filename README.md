# 🎮 Capture Monster Game - Java Mini Game Project

A 2D Java-based mini game where players can move, attack, and capture monsters on a tile-based map.  
This project is open for community contributions focusing on AI pathfinding, visual effects, item mechanics, and design.

---

## 📦 Project Structure
src/
├── Main.java # Entry point
├── GameFrame.java # Main game window
├── GameMap.java # Map logic
├── Actor.java, Mob.java # Characters and monsters
├── UI.java, Menu.java # User interface
├── image/ # In-game visual resources
└── ... # Other supportive classes


---

## 🕹️ Features

- Basic movement, UI interaction
- Multiple monsters and player characters
- Modular map structure
- Pre-designed hooks for:
  - BFS/DFS monster AI
  - Attack effects
  - Background/environment rendering
  - Item usage
  - UI and actor visual updates

---

## 📌 Contribution Tasks (open issues)

We welcome all contributions! Current available tasks include:
- #3 Monster movement (BFS/DFS)
- #2 UI design
- #1 Actor improvement
- #4 Map design
- #5 Monster/Character Art
- #6 Design and use of items
- #7 Air wall setting

You can find all open issues here:  
 [Issue Tracker](https://github.com/FLOSRC-LSC/java-RPG/issues)

---

## Getting Started

### Requirements
- Java 8+
- A Java IDE (IntelliJ, Eclipse, VSCode with Java extension)

### ▶Run the Game
```bash
javac src/Main.java
java -cp src Main
