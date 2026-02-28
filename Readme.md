# AI Algorithms Showcase

This repository contains implementations of various fundamental Artificial Intelligence (AI) algorithms, primarily focusing on search and optimization techniques. It's designed to demonstrate and explore how these algorithms work in practice.

## Algorithms Implemented

### 1. Alpha-Beta Pruning (`alpha-beta-prunning.py`)

This script implements the Alpha-Beta Pruning algorithm, an optimization technique for the minimax algorithm. It's used in decision-making problems, particularly in games, to reduce the number of nodes evaluated in the search tree.

### 2. Hill Climbing (`hill_climbing.py`)

The `hill_climbing.py` file demonstrates the Hill Climbing algorithm, a local search optimization technique. It iteratively moves towards a better solution by selecting the neighbor with the best heuristic value, aiming to find a local optimum.

### 3. A* Search Algorithm (`A*_algorithm.py`)

This script provides an implementation of the A* search algorithm. A* is an informed search algorithm that finds the shortest path between nodes in a weighted graph. It balances the cost to reach a node (`g-cost`) with an estimated cost to the goal (`h-cost`) using a heuristic function.

### 4. Breadth-First Search (BFS) and Depth-First Search (DFS) (`bfs_dfs.py`)

The `bfs_dfs.py` file showcases two essential graph traversal algorithms:
- **Breadth-First Search (BFS):** Explores the graph level by level, typically used for finding the shortest path in unweighted graphs.
- **Depth-First Search (DFS):** Explores as far as possible along each branch before backtracking, useful for tasks like topological sorting or finding connected components.

python alpha-beta-prunning.py
python hill_climbing.py
python A*_algorithm.py
python bfs_dfs.py
Project Structure
.idea/: Contains IDE-specific configuration files (e.g., for JetBrains IDEs). These are generally not needed for running the code.
alpha-beta-prunning.py: Implementation of Alpha-Beta Pruning.
hill_climbing.py: Implementation of the Hill Climbing algorithm.
A*_algorithm.py: Implementation of the A* search algorithm.
bfs_dfs.py: Implementations of BFS and DFS.