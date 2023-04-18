# Pathfinding e-learning tool

Hello and thank you for visiting Pathfinding Visualizer! I created this app because I was interested by pathfinding algorithms and wanted to see them in action. I hope you enjoy experimenting with this visualisation tool as much as I did creating it. You may find it at  (use Google Chrome!).

## Get to Know the Algorithms

The following algorithms are supported by this application: 

**The Algorithm of Dijkstra** (weighted): the grandfather of pathfinding algorithms; ensures the shortest route.

**A Search** (weighted): possibly the best pathfinding method; employs heuristics to discover the shortest path significantly quicker than Dijkstra's method.

**Greedy First-Page Search** (weighted): a quicker, more heuristic-heavy variant of A*; does not always find the shortest path.

**Swarm Algorithm** (weighted): a hybrid of Dijkstra's Algorithm and A* that does not always find the shortest path.

**Algorithm of Convergent Swarms** (weighted): Swarm's quicker, more heuristic-heavy variant; does not guarantee the shortest path.

**Bidirectional Swarm Optimisation** Swarm from both sides; does not ensure the quickest path

**Search by Breath** (unweighted): an excellent method that ensures the shortest path.

**In-Depth Search** (unweighted): a poor pathfinding algorithm that does not guarantee the shortest path.

I added a **Recursive Division** Maze Generation technique to the pathfinding algorithms outlined above.





## More about the Swarm Algorithm

The algorithm is basically a hybrid of Dijkstra's Algorithm and A* Search; more specifically, while A* converges to the target node, Dijkstra's searches a large number of neighbouring nodes around the start node. The method distinguishes itself from A* by employing heuristics: it constantly updates nodes' distance from the start node while accounting for their predicted distance from the destination node. This effectively "balances" the difference in total distance between nodes closer to the start node and nodes closer to the goal node, resulting in the Swarm Algorithm's triangle-like form.






