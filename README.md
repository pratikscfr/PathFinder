# PathFinder
Visualizer for pathfinding algorithms.
## Dijkstra
Dijkstra's algorithm works by first adding the starting node to a priority queue. It then takes the top node in the priority queue and looks at all of the nodes surrounding it. If the nodes are valid positions then they are added to the priority queue and the top node in the queue is deleted. These nodes that are added to the queue also have a knowledge of what node they were explored from (ie. their parent node) This process is continued until a node is discovered with the same location as the finish node. From that node, a path is created by retracing the steps to the starting node.
