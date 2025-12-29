Pong Game in C++ using Raylib

This project is a complete implementation of the classic Pong game written in C++ using the Raylib graphics library. It demonstrates real-time rendering, keyboard input handling, basic AI behavior, collision physics, score tracking, and persistent high-score storage.

The game supports multiple modes, spin mechanics on the ball, and acceleration-based difficulty progression. It is structured around a main game loop with clear state transitions and rendering stages.

Features

Implemented in C++ with Raylib

60 FPS real-time game loop

Single-player mode with AI opponent

Two-player local multiplayer mode

High-score arcade mode with persistent storage to file

Ball spin and speed scaling based on paddle hit location

Collision detection with paddles and screen boundaries

Game over screen and restart mechanics

Keyboard-based controls

Simple menu system for selecting game mode

Game Modes

Single Player
Play against a computer-controlled paddle with adaptive behavior.

Two Player
Local multiplayer where both paddles are controlled manually.

High Score Mode
Score as many points as possible and save the highest score to file.

Controls
Player 1

W: Move paddle up

S: Move paddle down

Player 2 (Two-player mode)

Up Arrow: Move paddle up

Down Arrow: Move paddle down

Menu and Game

1: Single-player mode

2: Two-player mode

3: High-score mode

Enter: Restart game after game over

Esc: Quit game window

Technical Details

Language: C++

Library: Raylib

Rendering: 2D raster graphics

Frame rate: 60 FPS

Persistent high score saved using C++ file I/O

AI paddle movement reacts to ball trajectory

Spin and speed scaling based on collision position on paddle

How to Build and Run

Install Raylib (consult official Raylib documentation for your OS)

Clone this repository

Compile using a C++17-compatible compiler and link Raylib

Example (Linux with g++ and pkg-config):

g++ main.cpp -o pong `pkg-config --libs --cflags raylib`


On Windows, compilation will depend on your Raylib setup (MinGW, MSVC, etc.). Follow the Raylib build guide and link the library accordingly.

Run the compiled executable to start the game.

File Structure

main.cpp – game source code

highscore.txt – auto-created file storing the best score

Concepts Demonstrated

event-driven loop programming

state management

basic physics and collision response

AI-controlled entity movement

persistent storage through file handling

2D rendering and animation

real-time input processing

Future Improvements

Sound effects and background music

Customizable difficulty levels

Pause menu

Better AI prediction logic

On-screen instructions overlay

Separate classes for paddles and ball (OOP refactor)
