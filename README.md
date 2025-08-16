# AI-Search-Algorithms
A Python implementation of BFS, DFS, UCS, and A* algorithms for pathfinding—applied to both Romania’s city network and a grid-based visualization.
This project demonstrates three search algorithms (BFS, DFS, UCS) for route planning in Romania and an A* pathfinding visualization on a grid.

## Features

### 1. Romania Route Planning
- **Graph Representation**: Cities and roads of Romania are modeled as a graph.
- **Algorithms**:
  - **BFS (Breadth-First Search)**: Finds the shortest path in terms of hops.
  - **DFS (Depth-First Search)**: Explores as far as possible along branches.
  - **UCS (Uniform Cost Search)**: Finds the path with the lowest cumulative cost.
- **Example**: Path from Bucharest (`Bu`) to Timisoara (`Ti`).

### 2. A* Pathfinding Visualization
- **Grid Environment**: 20x20 grid with walls and start/goal positions.
- **A* Algorithm**: Finds the shortest path using Manhattan distance heuristic.
- **Visualization**: 
  - Green: Start position (bottom-left).
  - Red: Goal position (top-right).
  - Blue: Visited nodes.
  - Cyan: Final path.

## How to Use

1. **Romania Route Planning**:
   - Run the code to see BFS, DFS, and UCS results for `Bu` to `Ti`.
   - Output includes the path and total cost.

2. **A* Visualization**:
   - The Pygame window opens automatically.
   - The algorithm runs once, showing the explored nodes and final path.

## Dependencies
- Python 3
- Libraries: `prettytable`, `heapq`, `pygame`

## Example Output (Romania)
BFS Path: ['Bu', 'Fa', 'Si', 'Ar', 'Ti']
BFS Cost: 568

DFS Path: ['Bu', 'Pi', 'Cr', 'Dr', 'Me', 'Lu','Ti']
DFS Cost: 615

UCS Path: ['Bu', 'Pi', 'Ri', 'Si', 'Ar', 'Ti']
UCS Cost: 536

## Example Output (Grid Pathfinding)
<img width="629" height="633" alt="image" src="https://github.com/user-attachments/assets/9a28e2ac-687b-46a4-93f8-1f100ff7202b" />
