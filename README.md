# path-finder-project
Dijkstra’s algorithm


#Dijkstra’s algorithm

Dijkstra’s algorithm is used to find the shortest path between two points in a graph by evaluating each node in the graph and calculating the distance from the starting node to each node in the graph.

We start by evaluating the starting node and assigning it a distance of 0. We evaluate each of the neighboring nodes and calculate the distance to each node. The algorithm selects the node with the smallest distance and adds it to the list of visited nodes.

Afterwards we evaluate the neighboring nodes of the newly added node and calculate the distances. The algorithm adds the node with the smallest distance to the list of visited nodes and continues this process until it reaches the destination node. As the algorithm evaluates each node, it keeps track of the distances and the path taken to reach each node. If a node is revisited with a shorter distance, the algorithm updates the distance and path to reflect the better route.

Dijkstra’s algorithm is widely used in navigation systems, logistics, and transportation planning: by efficiently evaluating each node and keeping track of the path taken, it helps find the optimal route between two points in a graph.

The algorithm starts by evaluating the starting node and assigning it a distance of 0. It then evaluates each of the neighboring nodes and calculates the distance to each node. The algorithm selects the node with the smallest distance and adds it to the list of visited nodes. It evaluates the neighboring nodes of the newly added node and calculates their distances.

It adds the node with the smallest distance to the list of visited nodes and continues this process until it reaches the destination node. As the algorithm evaluates each node, it keeps track of the distances and the path taken to reach each node. If a node is revisited with a shorter distance, the algorithm updates the distance and path to reflect the better route. 
Key Changes for D* Lite:

Dijkstra’s Algorithm - Complexity
▶ Claim: The worst case runtime of the algorithm is O(n2)
(addition & comparisons), where n is the number of vertices.
1. The algorithm terminates in no more than n iterations.
2. At each iteration,
▶ We can determine v k with no more than n − 1 comparison.
▶ We can update c(·) by doing no more than 2(n − 1) additions
and comparisons.
▶ In the worst case, the algorithm completes in
n × 3(n − 1) = 3n2 − 3n additions & comparisons.
▶ It may take much more steps if we don’t use the Dijkstra’s
algorithm.

Summary
▶ A typical flow for problem solving:
modelling −→ design & apply algorithm −→ analyze output
▶ These steps are inter-connected but requires good
understanding of the problem and good modelling.
▶ Back to the Dijkstra’s algorithm, note that it is one of the
most popular algorithms for graph with applications to:
▶ Google Maps, Rubik’s cube, etc.
▶ Extensions: graph with cycles, random shortest path (to
model congestion)


#Dynamic A*

Dynamic Updates: D* Lite involves dynamic updates to the graph, which requires additional logic to handle changes in the environment. This code provides a basic framework but does not include those dynamic updates.
Heuristic and Cost Adjustments: The heuristic function and cost calculations may need to be adjusted if the environment changes during execution.
Initial Setup: Initialize nodes and costs similar to A*, but prepare for dynamic cost changes.

To convert the A* algorithm to D* (Dynamic A*), we need to accommodate changes in the grid dynamically as the search progresses. Here's a simplified version of how you might modify the code:

This version is a starting point and would need further development for full D* Lite functionality, including handling changes in the environment.
