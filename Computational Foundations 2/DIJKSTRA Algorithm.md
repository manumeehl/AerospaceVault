- Used for efficient path planning in a network

Consists of multiple *node* connected by *links*.
Each *link* has an assigned cost value which describes the required expense to get from one *node* to each other.
This knowledge base is called *metric*.

Procedure
1. Initialization
	- Create a list of all unvisited *nodes*
	- Set Cost of reaching origin node S to 0
	- Set cost of all other nodes to infinity
2. Set (random) *node* with lowest cost in network to __visited__
3. Add the cost of the current __visited__ *node* to the cost of reaching the nearest neighbours.
4. Replace cost of neighbour *nodes* by those of step __3__ if they are smaller.
5. If not all *nodes* have been visited, continue with at __2__, else end algorithm.

##### Why is A* faster?
- A* algorithm uses a heuristic function h(n) to estimate the remaining cost to the goal, in addition to the actual cost g(n) used by Dijkstra's algorithm.
- As long as the heuristic h(n) is admissible (never overestimates the actual cost), A* is guaranteed to find the shortest path.
- The quality of the heuristic function is crucial for the performance of A*, allowing it to often explore the search space more efficiently than Dijkstra's algorithm.