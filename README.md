# Maze-Game-using-BFS-DFS-

# Explanation of the code:
# ________________________

This code defines two search algorithms, Breadth-First Search (BFS) and Depth-First Search (DFS), and applies them to a maze represented as a 2D list of characters and integers. The maze contains the starting point 'A', the goal point 'G', and obstacles represented as 1s.

The get_neighbors function takes a node and the maze as input and returns a list of all neighboring nodes that are not obstacles. It checks if the neighboring nodes are within the maze boundaries and not obstacles by checking their values in the maze list.

The bfs function implements the Breadth-First Search algorithm. It first finds the start and goal nodes by iterating through the maze list. It then initializes a frontier with a list containing the start node, and an explored set. It uses a while loop to continue searching until the frontier is empty. In each iteration of the loop, it pops the first element from the frontier list, which represents the next node to be explored. It then checks if the current node is the goal node, in which case it returns the path and the number of steps. If the current node is not the goal node, it adds it to the explored set and expands the frontier by adding its neighbors that have not been explored before. It does this by creating a new path that includes the current node's neighbors and appending it to the frontier list.

The dfs function implements the Depth-First Search algorithm, which is similar to the BFS algorithm, except that it uses a stack instead of a queue to keep track of the nodes to be explored. It follows the same logic as the BFS algorithm to find the path from the start node to the goal node.

Finally, the code applies the BFS and DFS algorithms to the maze and prints the resulting paths and the number of steps required to reach the goal node from the start node for each algorithm.

# OUTPUT:
# _______

![1](https://user-images.githubusercontent.com/92660593/221215968-4cba31ef-4b00-4ee0-8be0-c8ff02a4e3eb.PNG)
