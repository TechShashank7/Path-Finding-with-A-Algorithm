# A* Pathfinding Algorithm

## Introduction
This project implements the **A* (A-Star) Pathfinding Algorithm** in Python. The A* algorithm is widely used in pathfinding and graph traversal, efficiently finding the shortest path between a start and goal point in a grid-based environment.

## Features
- Grid-based representation of the environment.
- Uses the **Manhattan Distance** heuristic for path estimation.
- Implements a **priority queue (Min-Heap)** for efficient node selection.
- Finds the shortest path while avoiding obstacles.
- Returns the path if found or `None` if no path exists.

## Algorithm Explanation
The A* algorithm works by evaluating nodes based on two factors:
1. **G-cost**: The actual movement cost from the start node to the current node.
2. **H-cost**: The heuristic estimated cost from the current node to the goal.

The total cost function is:
```
F = G + H
```
A* expands the node with the lowest **F-cost**, ensuring an optimal path.

## Installation & Usage
### Prerequisites
Ensure you have Python installed on your system.

### Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/a-star-pathfinding.git
   cd a-star-pathfinding
   ```
2. Run the Python script:
   ```bash
   python astar.py
   ```
