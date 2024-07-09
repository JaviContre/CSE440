# Pacman Search Algorithms Project
Project Description
This project involves implementing and applying various search algorithms to solve different search problems within the Pacman AI framework. The goal is to navigate Pacman through mazes, collect food, and achieve specific goals using algorithms such as Depth-First Search (DFS), Breadth-First Search (BFS), Uniform Cost Search (UCS), and A* search. The project also includes the development of heuristic functions and custom search problems.

Implemented Algorithms
1. Depth-First Search (DFS)
DFS is implemented to explore a maze by going as deep as possible along each branch before backtracking. It uses a stack data structure to keep track of the nodes to be explored. This method ensures that Pacman reaches a goal state by exploring all possible paths deeply.

2. Breadth-First Search (BFS)
BFS is implemented to explore the maze level by level. It uses a queue data structure to explore all nodes at the present depth level before moving on to nodes at the next depth level. This method guarantees finding the shortest path to the goal state in an unweighted maze.

3. Uniform Cost Search (UCS)
UCS is implemented to explore the maze using a priority queue, expanding the least costly node first. This algorithm is useful for finding the least-cost path to the goal state, especially when different paths have different costs.

4. A* Search
A* search is implemented to combine the strengths of UCS and greedy best-first search. It uses a priority queue and a heuristic function to estimate the cost to reach the goal. This heuristic-driven approach helps in efficiently finding the optimal path by considering both the cost so far and the estimated cost to the goal.

5. Heuristic Functions
Custom heuristic functions are developed to guide the A* search algorithm. These functions estimate the remaining cost to reach the goal state. Examples include the Manhattan distance and Euclidean distance, which are used depending on the problem's requirements.

6. Custom Search Problems
Custom search problems are created to handle specific scenarios within the Pacman game. These problems define the state space, initial state, goal state, and the actions available to Pacman. By defining these elements, the search algorithms can be applied to solve these custom scenarios effectively.

Conclusion
This project demonstrates the application of fundamental search algorithms to navigate Pacman through various mazes and scenarios. By implementing DFS, BFS, UCS, A* search, and heuristic functions, the project provides a comprehensive understanding of search strategies in artificial intelligence. The custom search problems further enhance the project's ability to address specific challenges within the Pacman framework.
