## Workshop_2

The traveler problem, also known as the traveling salesman problem (TSP), is a classic challenge in the field of combinatorial optimization. It consists of finding the shortest route that visits all cities exactly once and returns to the starting point. Despite its apparent simplicity, the TSP is NP-hard, which implies that finding the optimal solution for a large number of cities is computationally expensive.
Our approach starts by generating random cities on a three-dimensional plane. Each city has unique coordinates and the distance between them is calculated to build a distance matrix. The ants, simulated as virtual agents, move randomly between cities using a probability that depends on several factors: Pheromones, distance, control parameters.
