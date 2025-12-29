# Pong Game in C++ using Raylib

This repository contains a complete implementation of the classic Pong game written in C++ using the Raylib graphics library. The project demonstrates real-time rendering, keyboard input handling, game-state management, basic AI paddle behavior, collision physics, score tracking, and persistent high-score storage.

---

## Features

- Implemented entirely in C++ using Raylib
- 60 FPS real-time game loop
- Single-player mode with AI opponent
- Two-player local multiplayer mode
- High-score arcade mode with persistent storage
- Ball spin and progressive speed increase
- Collision detection with paddles and screen edges
- Restartable game-over state
- Simple menu-based mode selection
- Keyboard controls for both players

---

## Game Modes

| Mode | Description |
|------|-------------|
| Single Player | Play against an AI paddle |
| Two Player | Local multiplayer mode |
| High Score Mode | Try to achieve and save the highest score |

High scores are written to `highscore.txt` using C++ file I/O.

---

## Controls

### Player 1
- `W` move paddle up  
- `S` move paddle down  

### Player 2 (Two-player mode)
- `UP ARROW` move paddle up  
- `DOWN ARROW` move paddle down  

### Menu and Game Actions
- `1` Single-player mode  
- `2` Two-player mode  
- `3` High-score mode  
- `ENTER` restart game after game over  
- `ESC` quit game  

---

## Technical Details

- Language: C++
- Library: Raylib
- Frame rate: 60 FPS
- Rendering: 2D graphics primitives
- Persistent high score using file handling
- Spin mechanics and velocity scaling based on paddle hit position
- AI paddle moves based on ball trajectory direction

---

## How to Build and Run

### Prerequisite

Install Raylib on your system. Follow the official Raylib documentation for your platform.

### Clone the repository

```bash
git clone https://github.com/your-username/pong-raylib-cpp.git
cd pong-raylib-cpp
