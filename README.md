# PathFinder
Visualizer for pathfinding algorithms.
## Dijkstra
Dijkstra's algorithm works by first adding the starting node to a priority queue. It then takes the top node in the priority queue and looks at all of the nodes surrounding it. If the nodes are valid positions then they are added to the priority queue and the top node in the queue is deleted. These nodes that are added to the queue also have a knowledge of what node they were explored from (ie. their parent node) This process is continued until a node is discovered with the same location as the finish node. From that node, a path is created by retracing the steps to the starting node.
## A*
A* works similarly to dijkstra by creating a priority queue of nodes and then adding new nodes to the queue by exploring the top node on the queue. However in A* the nodes are placed into the queue with a heuristic of distance to the finish node. This means that the node at the top of the queue is always the node closest to the finish node.
