Here are the algorithms for the given problems:

1. **8-Puzzle Problem**:
   - **Algorithm**:
     1. Define the start and goal states of the 8-puzzle.
     2. Use BFS (Breadth-First Search) or A* algorithm to explore the state space.
     3. For BFS: Enqueue the initial state and explore neighboring states.
     4. For A*: Use a priority queue with a heuristic (e.g., Manhattan distance).
     5. Continue until the goal state is reached.
     6. Backtrack to find the solution path.

2. **8-Queen Problem**:
   - **Algorithm**:
     1. Start with an empty chessboard.
     2. Place a queen in the first row.
     3. For each subsequent row, place a queen such that no two queens threaten each other.
     4. Use recursion to backtrack if no valid placement is possible.
     5. The solution is found when all queens are placed.

3. **Water Jug Problem**:
   - **Algorithm**:
     1. Define two jugs with capacities A and B.
     2. Use BFS or DFS to explore possible states of water levels in the jugs.
     3. State transitions include filling, emptying, or transferring water between jugs.
     4. Continue exploring until one jug has the desired amount of water.

4. **Crypt-Arithmetic Problem**:
   - **Algorithm**:
     1. Treat each letter as a variable.
     2. Assign digits (0-9) to each letter, ensuring no two letters share the same digit.
     3. Use backtracking to explore different digit assignments.
     4. If a valid solution satisfies the arithmetic equation, print the result.

5. **Missionaries and Cannibals Problem**:
   - **Algorithm**:
     1. Represent the state as the number of missionaries and cannibals on each riverbank.
     2. Use BFS or DFS to explore transitions, moving missionaries and cannibals.
     3. Ensure that cannibals never outnumber missionaries on either side.
     4. The goal is to get all the missionaries and cannibals across the river safely.

6. **Vacuum Cleaner Problem**:
   - **Algorithm**:
     1. Represent the environment as a grid of rooms, each either clean or dirty.
     2. Use a reflex agent or search-based method to explore the grid.
     3. Clean a room if it's dirty, then move to the next room.
     4. The goal is achieved when all rooms are clean.

7. **BFS (Breadth-First Search) Algorithm**:
   - **Algorithm**:
     1. Start from the initial node or root.
     2. Enqueue the starting node into a queue.
     3. While the queue is not empty, dequeue a node and explore its neighbors.
     4. Mark nodes as visited and enqueue unvisited neighbors.
     5. Stop if the goal is found, otherwise continue.

8. **DFS (Depth-First Search) Algorithm**:
   - **Algorithm**:
     1. Start from the initial node or root.
     2. Push the initial node into a stack.
     3. While the stack is not empty, pop a node and explore its neighbors.
     4. Mark nodes as visited and push unvisited neighbors into the stack.
     5. Stop if the goal is found, otherwise continue.

9. **Travelling Salesman Problem (TSP)**:
   - **Algorithm**:
     1. Represent cities as nodes and distances as edges.
     2. Use dynamic programming, greedy methods, or approximation algorithms to find the shortest tour.
     3. For dynamic programming: Use a bitmask to track visited cities and minimize the total distance.
     4. Return to the starting city after visiting all cities.

10. **A* Algorithm**:
    - **Algorithm**:
      1. Start from the initial node and use a priority queue to manage nodes.
      2. For each node, calculate the cost to the goal using a heuristic (e.g., Manhattan distance).
      3. Dequeue the node with the lowest cost and explore its neighbors.
      4. If the goal is reached, stop the search.
      5. Otherwise, update the costs of neighbors and continue exploring.
