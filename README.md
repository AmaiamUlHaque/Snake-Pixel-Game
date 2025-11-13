# Classic Pixel Snake Game

A complete C++ implementation of the classic Snake game featuring modular object-oriented design, dynamic gameplay mechanics, and cross-platform compatibility.



## Final Results

### Results:

ADD PICS, GIFS, VIDEOS!!!

### Game Mechanics
- **Movement**: Use `W A S D` keys for directional control (90° turns only, no 180° reversals)
- **Speed Control**: 
  - 5 speed levels available
  - `E` key increases game speed
  - `Q` key decreases game speed  
- **Game Controls**:
  - `ESC` key to exit game
  - `F` key to regenerate food (debug feature --> developer's secret... the users must not find out.....hehe)

### Game Features:

- Smooth snake movement with wrap-around boundaries
- Dynamic food generation avoiding snake body collisions
- Real-time score tracking and display
- Adjustable game speed (5 levels)
- Self-collision detection ending the game
- Clean visual display with bordered game area
- Stable 60 FPS equivalent gameplay across speed settings



## Purpose

This project demonstrates core software engineering principles through the development of a fully-featured Snake game. The implementation focuses on:
- Object-oriented programming with proper class separation
- Memory management and rule of three compliance
- Real-time game loop architecture
- Cross-platform terminal handling
- Modular game component design



## Technical Overview

### Technical Architecture
The game follows a modular design pattern with these core components:

**Game Loop Structure:**

    Initialize() → while(!exit) { GetInput() → RunLogic() → DrawScreen() → LoopDelay() } → CleanUp()

**Core Classes:**
- `GameMechs`: Central game state management (score, board, food, flags)
- `Player`: Snake entity with movement logic and collision detection
- `objPos` & `objPosArrayList`: Position tracking and snake body management
- `MacUILib`: Cross-platform terminal I/O abstraction

#### Project Structure:

```text
Snake-Pixel-Game/
├── GameMechs.[h/cpp]           # Game state management
├── Player.[h/cpp]              # Snake entity logic  
├── objPos.[h/cpp]              # Position data structure
├── objPosArrayList.[h/cpp]     # Snake body container
├── MacUILib.[h/cpp]            # Platform abstraction
└── Project.cpp                 # Main game loop
```

### Building and Running

```bash
# TO RUN
# Just click and run the file from the file explorer in this repo's path:
Project.exe


# TO BUILD AND RUN
# Build the game from within the terminal with the project folder's path:
make
# Click and run the game file:
./Project.exe

```



## Skills Obtained

### Programming & Language Skills
- ✅ Advanced C++ Object-Oriented Programming including class architecture, encapsulation, and abstraction principles
- ✅ Comprehensive memory management implementing Rule of Three with dynamic allocation and pointer arithmetic
- ✅ Custom data structure development and algorithm optimization using Standard Template Library concepts

### Software Architecture & System Design
- ✅ Modular system architecture with clear separation of game logic, rendering, and input handling subsystems
- ✅ Cross-platform development implementing POSIX/Windows compatibility layers and platform abstraction
- ✅ Clean API design between game components and platform layers with system integration

### Game Development & Real-Time Systems
- ✅ Real-time game loop architecture implementing frame-based rendering systems and state management
- ✅ Non-blocking keyboard input handling with state machine implementation for responsive controls
- ✅ Character-based user interface development with terminal rendering and screen buffering techniques

### Algorithms & Data Structures
- ✅ Efficient collision detection algorithms for self-collision and food consumption detection systems
- ✅ Custom array list implementation for dynamic snake body management with optimized data structures
- ✅ Spatial algorithms for position-based calculations and wrap-around boundary handling mechanics


---
---

*This project successfully demonstrates professional-grade C++ development practices in a practical game implementation.* 