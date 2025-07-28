
# Pathfinding Visualizer

_This is a Pathfinding Visualizer built using JavaScript, which demonstrates how different pathfinding algorithms work to find the shortest path between a start and end node in a grid. It visually shows how the algorithms traverse the grid, handle obstacles, and reach the destination_

Live _<ins>[here](https://darshan-1820.github.io/Pathfinding-Visualizer/)_</ins>

## Features

> Interactive grid with adjustable walls

> Visualization of multiple algorithms

> Clear and restart controls

> Responsive and lightweight UI

> Real-time animation of visited nodes and the shortest path

## Algorithms Implemented

### 1. Dijkstra’s Algorithm
> Guarantees the shortest path
> Weighted graph support
> Time Complexity: O(V²) or O((V + E) log V) with min-heap
> Use Cases: GPS navigation, OSPF routing [Learn More](https://en.wikipedia.org/wiki/Open_Shortest_Path_First)

### 2. A* (A-Star) Search 
> Uses heuristics for optimized search
> Faster than Dijkstra in most practical cases
> Time Complexity: O(E) with a good heuristic
> Use Cases: Game AI, robot navigation, delivery path planning

### 3. Breadth-First Search (BFS)
> Guarantees the shortest path in unweighted graphs
> Explores level-by-level
> Time Complexity: O(V + E)
> Use Cases: Social networking suggestions, shortest path in mazes

### 4. Depth-First Search (DFS)
> Explores as deeply as possible before backtracking
> May not find the shortest path
> Time Complexity: O(V + E)
> Use Cases: Maze generation, topological sort, [Learn More](https://en.wikipedia.org/wiki/Topological_sorting), cycle detection [Read More](https://www.geeksforgeeks.org/dsa/detect-cycle-in-a-graph/)

### How to Run Locally
```
git clone https://github.com/Darshan-1820/Pathfinding-Visualizer.git
cd Pathfinding-Visualizer
open index.html
```

