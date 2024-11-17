# path-finder-proj
Dijkstra’s algorithm


Dijkstra’s algorithm

Dijkstra’s algorithm is used to find the shortest path between two points in a graph by evaluating each node in the graph and calculating the distance from the starting node to each node in the graph.

We start by evaluating the starting node and assigning it a distance of 0. We evaluate each of the neighboring nodes and calculate the distance to each node. The algorithm selects the node with the smallest distance and adds it to the list of visited nodes.

Afterwards we evaluate the neighboring nodes of the newly added node and calculate the distances. The algorithm adds the node with the smallest distance to the list of visited nodes and continues this process until it reaches the destination node. As the algorithm evaluates each node, it keeps track of the distances and the path taken to reach each node. If a node is revisited with a shorter distance, the algorithm updates the distance and path to reflect the better route.

Dijkstra’s algorithm is widely used in navigation systems, logistics, and transportation planning: by efficiently evaluating each node and keeping track of the path taken, it helps find the optimal route between two points in a graph.

The algorithm starts by evaluating the starting node and assigning it a distance of 0. It then evaluates each of the neighboring nodes and calculates the distance to each node. The algorithm selects the node with the smallest distance and adds it to the list of visited nodes. It evaluates the neighboring nodes of the newly added node and calculates their distances.

It adds the node with the smallest distance to the list of visited nodes and continues this process until it reaches the destination node. As the algorithm evaluates each node, it keeps track of the distances and the path taken to reach each node. If a node is revisited with a shorter distance, the algorithm updates the distance and path to reflect the better route. 
Key Changes for D* Lite:

Dynamic A*

Dynamic Updates: D* Lite involves dynamic updates to the graph, which requires additional logic to handle changes in the environment. This code provides a basic framework but does not include those dynamic updates.
Heuristic and Cost Adjustments: The heuristic function and cost calculations may need to be adjusted if the environment changes during execution.
Initial Setup: Initialize nodes and costs similar to A*, but prepare for dynamic cost changes.

To convert the A* algorithm to D* (Dynamic A*), we need to accommodate changes in the grid dynamically as the search progresses. Here's a simplified version of how you might modify the code:

This version is a starting point and would need further development for full D* Lite functionality, including handling changes in the environment.
