# Maze Solver with DFS, BFS, and A\* Algorithms

This repository contains a Python implementation of three search algorithms—**Depth-First Search (DFS)**, **Breadth-First Search (BFS)**, and **A\***—to solve a randomly generated maze. The project demonstrates how these algorithms navigate from the start to the goal while avoiding walls, with visualizations to showcase the paths found.

## Key Features
- **Maze Generation**: Randomly generates mazes with customizable wall probabilities.
- **Search Algorithms**:
  - **DFS**: Explores as far as possible along each branch before backtracking.
  - **BFS**: Explores all neighbors at the present depth level before moving deeper.
  - **A\***: Uses a heuristic to efficiently find the shortest path.
- **Visualization**: Plots the maze and highlights the path found by each algorithm.
- **Comparison**: Discusses the advantages and disadvantages of each algorithm in the context of the maze problem.

## How to Use
1. Clone the repository.
2. Install the required libraries: `pip install numpy matplotlib`.
3. Run the Jupyter notebook to generate mazes, apply search algorithms, and visualize the results.

## Why This Project?
This project is a great way to understand the fundamentals of search algorithms in AI and their applications in pathfinding problems. It also provides a hands-on opportunity to explore the trade-offs between uninformed (DFS, BFS) and informed (A\*) search strategies.

## Requirements
- Python 3.x
- Libraries: `numpy`, `matplotlib`, `queue`, `heapq`, `random`
