[🇺🇸 English](README.md) · **🇧🇷 Português (Brasil)**

# Jogos para criar e me tornar um desenvolvedor de jogos melhor

Um roteiro prático: estou construindo uma série de jogos pequenos a médios, em ordem de dificuldade, para aprender as habilidades que um desenvolvedor de jogos precisa. O caminho termina com um jogo meu, lançado publicamente.

## Por que este projeto existe

Quero ganhar experiência real terminando jogos, e não só lendo sobre eles. Cada projeto isola algumas habilidades novas (colisão, IA, geração procedural, parsing, renderização, ...), então a dificuldade cresce aos poucos. Quando eu conseguir construir um FPS com conforto, devo estar pronto para projetar, construir e lançar meu próprio jogo, e me estabelecer como desenvolvedor de jogos.

## Como funciona

- Este repositório é o hub: o roteiro, a tabela de progresso e os links para todos os jogos.
- Cada jogo fica em seu próprio repositório, com um `README.md` que cobre a proposta, as habilidades que pretendo praticar e o que aprendi depois.
- O roteiro completo (foco, status, engine, linguagem, notas) fica na planilha `Games to Create to Become a Better Game Developer.xlsx`.
- Engine e linguagem são escolhidas para cada jogo quando eu começo.
- Um repositório de jogo só é criado quando eu começo aquele jogo, para que repositórios vazios não se acumulem.
- Os arquivos `docs/game-readme-template.md` (inglês) e `docs/game-readme-template-ptbr.md` (português) são os templates de todo README de jogo.

## Progresso: 1/33 concluído

### Fase 1 - Fundamentos de programação

| # | Jogo | Foco | Status |
|---|------|-------|--------|
| 1 | [Text-based adventure](https://github.com/ghiordanobruno/text-based-adventure) | Basic I/O, Code Structure, Branching Logic, Game State | ✅ Concluído |
| 2 | [Tic-Tac-Toe](https://github.com/ghiordanobruno/tic-tac-toe) | 2D Arrays, Turn Logic, Minimax Algorithm | 🟨 Em andamento |

### Fase 2 - Básico de 2D em tempo real

| # | Jogo | Foco | Status |
|---|------|-------|--------|
| 3 | Conway's Game of Life | Cellular Automata, Grid Logic, Mouse Input, Simple Rendering/Animation | ⬜ Não iniciado |
| 4 | Pong | Game Loop, Delta Time, Basic Collision (AABB), Basic AI, Basic Physics | ⬜ Não iniciado |
| 5 | Breakout | Collision Response, Ball Reflection, Basic Physics, Level Layouts | ⬜ Não iniciado |
| 6 | Snake | Linked Lists / Queues, Grid Movement, Keyboard Input | ⬜ Não iniciado |
| 7 | Tetris | Matrix Rotation, Collision Against a Grid, Line Clearing, Timers, Score/Level Progression | ⬜ Não iniciado |
| 8 | Asteroids | Trigonometry, Vectors, Inertia Physics, Screen Wrapping, Circle Collision, Particles | ⬜ Não iniciado |
| 9 | Space Invaders | Entity Management, Sprites, Wave Patterns, Shooting/Cooldowns, Basic Sound | ⬜ Não iniciado |

### Fase 3 - Algoritmos e conteúdo

| # | Jogo | Foco | Status |
|---|------|-------|--------|
| 10 | Minesweeper | Flood Fill, Recursion/BFS, Grid Data Model, Mouse Input (Left/Right Click) | ⬜ Não iniciado |
| 11 | Sudoku | Backtracking, Constraint Checking, Basic Procedural Generation | ⬜ Não iniciado |
| 12 | Maze Generator | Procedural Generation, DFS / Randomized Prim, Graph Basics | ⬜ Não iniciado |
| 13 | A* Pathfinding Visualizer | Pathfinding (A*, Dijkstra, BFS), Heuristics, Priority Queues, Visualization | ⬜ Não iniciado |
| 14 | Pacman | Levels/Tilemaps, Finite State Machines, Ghost AI, Pathfinding, Animation | ⬜ Não iniciado |
| 15 | Perlin Noise Terrain | Advanced Procedural Generation, Perlin/Simplex Noise, Octaves, Interpolation | ⬜ Não iniciado |
| 16 | Tile-Based Editor | File I/O, Serialization, GUI Creation, Tilemaps, Undo/Redo | ⬜ Não iniciado |

### Fase 4 - Estruturas de dados e parsing

| # | Jogo | Foco | Status |
|---|------|-------|--------|
| 17 | Brainfuck Interpreter | Basic Parsing, Interpreters, Memory Model, Loops/Jump Tables | ⬜ Não iniciado |
| 18 | Hash Table | Hashing, Collision Handling, Atypical Linked Lists, Dynamic Resizing | ⬜ Não iniciado |
| 19 | JSON Parser | Advanced Parsing, Tokenizer/Lexer, Recursive Descent, Complex Data Structures | ⬜ Não iniciado |
| 20 | Quadtree Spatial Partitioning | Trees, Spatial Data Structures, Broad-Phase Collision, Profiling | ⬜ Não iniciado |

### Fase 5 - Jogos completos e simulação

| # | Jogo | Foco | Status |
|---|------|-------|--------|
| 21 | Falling Sand Game | Particle Simulation, Cellular Rules, Complex GUI, Performance Optimization | ⬜ Não iniciado |
| 22 | Platformer Game | Rigid Body Physics, Tilemap Collision, Camera, Sprite Animation, Game Feel | ⬜ Não iniciado |
| 23 | Top-Down Shooter | Projectiles, Object Pooling, Enemy Steering/AI, Wave Spawning, Audio | ⬜ Não iniciado |
| 24 | Galcon | Basic AI, Real-Time Strategy Rules, Swarm Movement, UI Selection | ⬜ Não iniciado |
| 25 | Roguelike Dungeon Crawler | Procedural Dungeons, Turn-Based Systems, Field of View, Entity-Component Design, Save/Load | ⬜ Não iniciado |
| 26 | Chess vs AI | Move Generation, Rules Engine, Minimax with Alpha-Beta Pruning, Evaluation Functions | ⬜ Não iniciado |

### Fase 6 - Engine e fundamentos 3D

| # | Jogo | Foco | Status |
|---|------|-------|--------|
| 27 | GIF Save/Load Algorithm | Advanced File I/O, Binary Formats, LZW Compression/Decompression, Bitwise Arithmetic | ⬜ Não iniciado |
| 28 | Simple Lua/Python game engine | Virtual Machines/Scripting Embedding, Basic Engine Architecture, Scene/Asset Management | ⬜ Não iniciado |
| 29 | Raycasting Renderer | Pseudo-3D Rendering, Ray-Grid Intersection (DDA), Texture Mapping, Player Camera | ⬜ Não iniciado |
| 30 | 3D Software Renderer | Linear Algebra, Matrices, Perspective Projection, Camera, Rasterization, Depth Buffer | ⬜ Não iniciado |

### Fase 7 - Projeto final

| # | Jogo | Foco | Status |
|---|------|-------|--------|
| 31 | Game Jam Entry (48h) | Scope Management, Rapid Prototyping, Finishing, Publishing a Build | ⬜ Não iniciado |
| 32 | FPS | 3D Rendering, 3D Collision, Player Controller, Enemy AI, Audio, Level Design | ⬜ Não iniciado |
| 33 | My Own Game | Game Design, Production Planning, Polish, Marketing, Release | ⬜ Não iniciado |

## Notas

Esta tabela é gerada a partir da planilha. Se a planilha e este arquivo divergirem, a planilha é a fonte da verdade até o README ser regenerado.
