**🇺🇸 English** · [🇧🇷 Português (Brasil)](README-ptbr.md)

# Games to Create to Become a Better Game Developer

A hands-on roadmap: I am building a series of small-to-medium games, ordered by difficulty, to learn the skills a game developer needs. The path ends with my own game, released publicly.

## Why this project exists

I want to gain real experience by finishing games, not just reading about them. Each project isolates a few new skills (collision, AI, procedural generation, parsing, rendering, ...), so the difficulty grows gradually. When I can build an FPS comfortably, I should be ready to design, build and release my own game, and establish myself as a game developer.

## How it works

- This repository is the hub: the roadmap, the progress table and links to every game.
- Each game lives in its own repository, with a `README.md` covering the proposal, the skills I expect to practice, and what I learned afterwards.
- The full roadmap (focus, status, engine, language, notes) lives in the spreadsheet `Games to Create to Become a Better Game Developer.xlsx`.
- Engine and language are chosen per game when I start it.
- A game repository is created only when I start that game, so empty repositories do not pile up.
- The `docs/game-readme-template.md` (English) and `docs/game-readme-template-ptbr.md` (Brazilian Portuguese) files are the templates for every game README. Every game repository has both `README.md` and `README-ptbr.md`, built from them.


## Progress: 1/33 completed

### Phase 1 - Programming Foundations

| # | Game | Focus | Status |
|---|------|-------|--------|
| 1 | [Text-based adventure](https://github.com/ghiordanobruno/text-based-adventure) | Basic I/O, Code Structure, Branching Logic, Game State | ✅ Completed |
| 2 | [Tic-Tac-Toe](https://github.com/ghiordanobruno/tic-tac-toe) | 2D Arrays, Turn Logic, Minimax Algorithm | 🟨 In Progress |

### Phase 2 - Real-Time 2D Basics

| # | Game | Focus | Status |
|---|------|-------|--------|
| 3 | Conway's Game of Life | Cellular Automata, Grid Logic, Mouse Input, Simple Rendering/Animation | ⬜ Not Started |
| 4 | Pong | Game Loop, Delta Time, Basic Collision (AABB), Basic AI, Basic Physics | ⬜ Not Started |
| 5 | Breakout | Collision Response, Ball Reflection, Basic Physics, Level Layouts | ⬜ Not Started |
| 6 | Snake | Linked Lists / Queues, Grid Movement, Keyboard Input | ⬜ Not Started |
| 7 | Tetris | Matrix Rotation, Collision Against a Grid, Line Clearing, Timers, Score/Level Progression | ⬜ Not Started |
| 8 | Asteroids | Trigonometry, Vectors, Inertia Physics, Screen Wrapping, Circle Collision, Particles | ⬜ Not Started |
| 9 | Space Invaders | Entity Management, Sprites, Wave Patterns, Shooting/Cooldowns, Basic Sound | ⬜ Not Started |

### Phase 3 - Algorithms & Content

| # | Game | Focus | Status |
|---|------|-------|--------|
| 10 | Minesweeper | Flood Fill, Recursion/BFS, Grid Data Model, Mouse Input (Left/Right Click) | ⬜ Not Started |
| 11 | Sudoku | Backtracking, Constraint Checking, Basic Procedural Generation | ⬜ Not Started |
| 12 | Maze Generator | Procedural Generation, DFS / Randomized Prim, Graph Basics | ⬜ Not Started |
| 13 | A* Pathfinding Visualizer | Pathfinding (A*, Dijkstra, BFS), Heuristics, Priority Queues, Visualization | ⬜ Not Started |
| 14 | Pacman | Levels/Tilemaps, Finite State Machines, Ghost AI, Pathfinding, Animation | ⬜ Not Started |
| 15 | Perlin Noise Terrain | Advanced Procedural Generation, Perlin/Simplex Noise, Octaves, Interpolation | ⬜ Not Started |
| 16 | Tile-Based Editor | File I/O, Serialization, GUI Creation, Tilemaps, Undo/Redo | ⬜ Not Started |

### Phase 4 - Data Structures & Parsing

| # | Game | Focus | Status |
|---|------|-------|--------|
| 17 | Brainfuck Interpreter | Basic Parsing, Interpreters, Memory Model, Loops/Jump Tables | ⬜ Not Started |
| 18 | Hash Table | Hashing, Collision Handling, Atypical Linked Lists, Dynamic Resizing | ⬜ Not Started |
| 19 | JSON Parser | Advanced Parsing, Tokenizer/Lexer, Recursive Descent, Complex Data Structures | ⬜ Not Started |
| 20 | Quadtree Spatial Partitioning | Trees, Spatial Data Structures, Broad-Phase Collision, Profiling | ⬜ Not Started |

### Phase 5 - Complete Games & Simulation

| # | Game | Focus | Status |
|---|------|-------|--------|
| 21 | Falling Sand Game | Particle Simulation, Cellular Rules, Complex GUI, Performance Optimization | ⬜ Not Started |
| 22 | Platformer Game | Rigid Body Physics, Tilemap Collision, Camera, Sprite Animation, Game Feel | ⬜ Not Started |
| 23 | Top-Down Shooter | Projectiles, Object Pooling, Enemy Steering/AI, Wave Spawning, Audio | ⬜ Not Started |
| 24 | Galcon | Basic AI, Real-Time Strategy Rules, Swarm Movement, UI Selection | ⬜ Not Started |
| 25 | Roguelike Dungeon Crawler | Procedural Dungeons, Turn-Based Systems, Field of View, Entity-Component Design, Save/Load | ⬜ Not Started |
| 26 | Chess vs AI | Move Generation, Rules Engine, Minimax with Alpha-Beta Pruning, Evaluation Functions | ⬜ Not Started |

### Phase 6 - Engine & 3D Foundations

| # | Game | Focus | Status |
|---|------|-------|--------|
| 27 | GIF Save/Load Algorithm | Advanced File I/O, Binary Formats, LZW Compression/Decompression, Bitwise Arithmetic | ⬜ Not Started |
| 28 | Simple Lua/Python game engine | Virtual Machines/Scripting Embedding, Basic Engine Architecture, Scene/Asset Management | ⬜ Not Started |
| 29 | Raycasting Renderer | Pseudo-3D Rendering, Ray-Grid Intersection (DDA), Texture Mapping, Player Camera | ⬜ Not Started |
| 30 | 3D Software Renderer | Linear Algebra, Matrices, Perspective Projection, Camera, Rasterization, Depth Buffer | ⬜ Not Started |

### Phase 7 - Capstone

| # | Game | Focus | Status |
|---|------|-------|--------|
| 31 | Game Jam Entry (48h) | Scope Management, Rapid Prototyping, Finishing, Publishing a Build | ⬜ Not Started |
| 32 | FPS | 3D Rendering, 3D Collision, Player Controller, Enemy AI, Audio, Level Design | ⬜ Not Started |
| 33 | My Own Game | Game Design, Production Planning, Polish, Marketing, Release | ⬜ Not Started |

## Notes

This table is generated from the spreadsheet. If the spreadsheet and this file disagree, the spreadsheet is the source of truth until the README is regenerated.
