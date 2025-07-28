
# Pathfinding Visualizer

_This is a Pathfinding Visualizer built using JavaScript, which demonstrates how different pathfinding algorithms work to find the shortest path between a start and end node in a grid. It visually shows how the algorithms traverse the grid, handle obstacles, and reach the destination_

Live _<ins>[here](https://darshan-1820.github.io/Pathfinding-Visualizer/)_</ins>

## Features

1. Interactive grid with adjustable walls

2. Visualization of multiple algorithms

3. Clear and restart controls

4. Responsive and lightweight UI

5. Real-time animation of visited nodes and the shortest path

## Algorithms Implemented

### 1. Dijkstra’s Algorithm
1. Guarantees the shortest path<br/>
2. Weighted graph support<br/>
3. Time Complexity: O(V²) or O((V + E) log V) with min-heap<br/>
4. Use Cases: GPS navigation, OSPF routing [Learn More](https://en.wikipedia.org/wiki/Open_Shortest_Path_First)<br/>

### 2. A* (A-Star) Search 
1. Uses heuristics for optimized search<br/>
2. Faster than Dijkstra in most practical cases<br/>
3. Time Complexity: O(E) with a good heuristic<br/>
4. Use Cases: Game AI, robot navigation, delivery path planning<br/>

### 3. Breadth-First Search (BFS)
1. Guarantees the shortest path in unweighted <br/>
2. Explores level-by-level<br/>
3. Time Complexity: O(V + E)<br/>
4. Use Cases: Social networking suggestions, shortest path in mazes<br/>

### 4. Depth-First Search (DFS)
1. Explores as deeply as possible before backtracking<br/>
2. May not find the shortest path<br/>
3. Time Complexity: O(V + E)<br/>
4. Use Cases: Maze generation, topological sort, [Learn More](https://en.wikipedia.org/wiki/Topological_sorting), cycle detection [Read More](https://www.geeksforgeeks.org/dsa/detect-cycle-in-a-graph/)<br/>

### How to Run Locally
```
git clone https://github.com/Darshan-1820/Pathfinding-Visualizer.git
cd Pathfinding-Visualizer
open index.html
```

