# path-finder-proj
A* algorithm + Dijkstra’s algorithm + Dynamic A*


Dijkstra’s algorithm

Dijkstra’s algorithm is used to find the shortest path between two points in a graph by evaluating each node in the graph and calculating the distance from the starting node to each node in the graph.

We start by evaluating the starting node and assigning it a distance of 0. We evaluate each of the neighboring nodes and calculate the distance to each node. The algorithm selects the node with the smallest distance and adds it to the list of visited nodes.

Afterwards we evaluate the neighboring nodes of the newly added node and calculate the distances. The algorithm adds the node with the smallest distance to the list of visited nodes and continues this process until it reaches the destination node. As the algorithm evaluates each node, it keeps track of the distances and the path taken to reach each node. If a node is revisited with a shorter distance, the algorithm updates the distance and path to reflect the better route.

Dijkstra’s algorithm is widely used in navigation systems, logistics, and transportation planning: by efficiently evaluating each node and keeping track of the path taken, it helps find the optimal route between two points in a graph.

The algorithm starts by evaluating the starting node and assigning it a distance of 0. It then evaluates each of the neighboring nodes and calculates the distance to each node. The algorithm selects the node with the smallest distance and adds it to the list of visited nodes. It evaluates the neighboring nodes of the newly added node and calculates their distances.

It adds the node with the smallest distance to the list of visited nodes and continues this process until it reaches the destination node. As the algorithm evaluates each node, it keeps track of the distances and the path taken to reach each node. If a node is revisited with a shorter distance, the algorithm updates the distance and path to reflect the better route. 

A* algorithm

A* algorithm (pronounced “A-star”) is a graph traversal and path search algorithm that uses heuristics to estimate the most efficient path.

The A* algorithm is a powerful tool for finding the shortest path between two points in a graph by exploring the graph. It uses a heuristic function to guide the search towards the destination. The heuristic function estimates the distance between the current node and the destination node and it is what makes the A* algorithm different from other pathfinding algorithms. This helps guide the algorithm towards the destination more efficiently, as it prioritizes nodes that are closer to the destination.

The A* algorithm is widely used in robotics, video games, and other applications where efficient navigation is required.

The algorithm starts by evaluating the starting point and calculating its “score”. This score includes the distance from the starting point to the current node, as well as an estimate of the remaining distance to the destination using a heuristic function.

Next, the algorithm explores the neighboring nodes of the current node and calculates their scores. It then selects the node with the lowest score and adds it to the list of visited nodes. The algorithm continues this process, evaluating nodes and adding them to the visited list, until it reaches the destination node.

Along the way, the algorithm keeps track of the path taken and the scores of the visited nodes. If a node is revisited with a lower score, the algorithm updates the node’s score and path to reflect the better route. Figure visually shows how the A* algorithm finds the optimal path from the starting point to the destination.
