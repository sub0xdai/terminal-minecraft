
# Terminal Minecraft

A simple 3D Minecraft-like game that runs in your terminal using ASCII characters.

## Features
- 3D raycasting engine
- Block placement and destruction
- Gravity simulation
- Terminal-based rendering with colors

## Controls
- W/S: Look up/down
- A/D: Look left/right
- I/K: Move forward/backward
- J/L: Strafe left/right
- Space: Place block
- X: Remove block
- Q: Quit

## Building
```
gcc -o minecraft minecraft.c -lm
```

## Running
```
./minecraft
```

## About
This project uses raycasting techniques to create a simple 3D Minecraft-inspired environment in your terminal. The world is rendered using ASCII characters with color highlights for selected blocks.

## Requirements
- GCC compiler
- Math library (-lm)
- Terminal with ANSI color support

