# AI Search Pacman (UC Berkeley)

This repository contains my implementations for classical AI search algorithms and heuristics
using the **UC Berkeley Pacman AI** framework.

## What I implemented
- Search algorithms: **DFS**, **BFS**, **Uniform Cost Search (UCS)**, **A\***
- Heuristic design for grid-based search problems
- **MST-based heuristic caching** for improved performance (where applicable)

## How to run
> The UC Berkeley framework runs from the terminal inside the project folder.

### Example commands
```bash
python pacman.py -l tinyMaze -p SearchAgent -a fn=bfs
python pacman.py -l mediumMaze -p SearchAgent -a fn=ucs
python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic
