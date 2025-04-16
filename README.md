# 🌀 Maze Runner - Console Puzzle Adventure

Welcome to **Maze Runner**, a dynamic and interactive console-based maze puzzle game written in **C++**. Navigate mazes, beat your best time, and challenge your pathfinding skills with three levels of difficulty.

---

## 🎮 About the Game

**Maze Runner** is a colorful console game where you guide a player (`P`) from the start point to the exit (`E`) through procedurally generated mazes. Designed for speed, logic, and challenge, it features:

- Real-time movement with trail tracking
- Live timer and path metrics
- Auto-generated mazes of varying difficulty
- High-score tracking per difficulty
- Optional hint/solution display

---

## 🛠️ Built With

- 💻 **C++**
- 🧱 **STL containers**: `vector`, `stack`, `queue`,`enum`, `array`, `pair`
- 🪟 **\<windows.h>**, **\<conio.h>** for console handling (Windows only)

---

## 📚 Data Structures Used

- `class` & `struct` – For Object Oriented Programming
- `vector<vector<char>>` – Maze grid representation
- `stack<pair<int,int>>` – Used in both maze generation (DFS) and player path tracking
- `queue<pair<int,int>>` – Utilized in BFS pathfinding algorithm
- `pair` – To make Data Structures that store 2 values
- `enum` – Game difficulty level & Console colours indicator
- `array` – For various small tasks
- `string` – Manage file I/O
- `vector<HighScore>` – Stores and manages high score entries
- `chrono::high_resolution_clock` – Precise game timing

---

## 📐 Algorithms Used

- **Depth-First Search (DFS)** – For procedural maze generation using a randomized backtracking algorithm
- **Breadth-First Search (BFS)** – For calculating and displaying the shortest solution path to the player
- **Sorting** – High scores are sorted using `std::sort`

---

## ✨ Features

- 🔄 **Procedural Maze Generation** – New layout every time!
- 🧭 **Path Visualization** – View the shortest solution with `F`
- ⌛ **Timer & Stats** – Tracks time and steps
- 🥇 **High Score System** – Keeps top 5 scores per difficulty
- ❓ **Help Menu** – New players can quickly learn how to play and win
- 🎨 **Colorful UI** – Vibrant visual feedback in the console
- 🔁 **Backtracking Logic** – Automatically recognizes and manages player backtracking
- 💾 **File Persistence** – Saves and loads highscores from `maze_scores.dat`
- 🪶 **Lightweight & Standalone** – No external libraries or dependencies — just pure C++!

---

## 📦 Installation Guide

> ⚠️ **Note**: This game runs on **Windows only** due to usage of Windows-specific APIs (`<windows.h>`, `<conio.h>`).

### Requirements

- A C++ compatible compiler (e.g., MSVC, MinGW, or g++)
- A Windows OS
- [Git](https://git-scm.com/) installed (optional for cloning repo)

### Step-by-Step Instructions

#### 🔧 Option 1: Using Command Line (g++/MinGW)

1. Open Command Prompt or PowerShell
2. Clone the repository (or download it manually)
   ```bash
   git clone https://github.com/Pal-Jalodara/Maze-Runner.git
   cd Maze-Runner
   ```
3. Compile the game using `g++`
   ```bash
   g++ mazeRunner.cpp -o mazeRunner
   ```
4. Run the game
   ```bash
   ./mazeRunner
   ```

#### 💻 Option 2: Using Visual Studio Code

1. Download the `mazeRunner.cpp` file.
2. Open `mazeRunner.cpp` file in **Visual Studio Code**
3. Build and run the project.

---

## 🕹️ How to Play

Use these keys to navigate and interact:

| Key                              | Action                          |
| -------------------------------- | ------------------------------- |
| `W`, `A`, `S`, `D` or Arrow Keys | Move the player                 |
| `F`                              | Toggle solution path            |
| `C`                              | Clear trail (reset player path) |
| `R`                              | Restart the current maze        |
| `H`                              | View high scores                |
| `Q`                              | Quit to menu                    |

**Goal**: Get from the `P` (Player) to the `E` (Exit) in the shortest time and steps possible.

---

## 📸 Screenshots


- **Main Menu**

![Screenshot 2025-04-16 021856](https://github.com/user-attachments/assets/4aa6223b-4f53-498e-b286-457f40ed01a2)

- **Game Help**

![Screenshot 2025-04-16 021952](https://github.com/user-attachments/assets/238ea75d-70ed-4ee4-aa54-13b25e01983c)

- **High Scores**

![Screenshot 2025-04-16 021931](https://github.com/user-attachments/assets/50e93251-df6d-4706-9194-f6e8ca6b2633)

- **Maze Gameplay**

![Screenshot 2025-04-16 022812](https://github.com/user-attachments/assets/816cdfde-47d4-45ad-a850-14beeeb9fd3e)

- **Victory Screen**

![Screenshot 2025-04-16 023109](https://github.com/user-attachments/assets/9cef04d6-13fe-4063-b49d-f4b453b34e3e)

---

## 🔧 Possible Improvements

- 🌐 **Cross-platform support** (replace WinAPI with cross-platform libraries)
- 🧩 **Multiple maze types** (hex, circular, etc.)
- 💣 **Add multiple modes** (Portal Run, BoomMaze)
- 🔊 **Sound Effects**
- 📊 **Detailed score analytics**
- 🌈 **Customizable themes & controls**
- 🎮 **Enhanced Graphics mode** (SFML)

---

## 👨‍💻 Developed by **Tech Titans**
This project is a group effort by four passionate developers:
- **Pal Jalodara (202401074)** 👨‍💻
- **Ved Dhanani (202401048)** 👨‍💻
- **Dev Sanghani (202401047)** 👨‍💻
- **Kevin Rank (202401091)** 👨‍💻

---
This project is open-source and free to use.

Enjoy exploring the maze! 🧭🔥
