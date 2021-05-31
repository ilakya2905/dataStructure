# Greedy Algorithm
1. An algorithm is designed to achieve optimum solution for a given problem. 

2. Greedy is an algorithmic paradigm that builds up a solution piece by piece, always choosing the next piece that offers the most obvious and immediate benefit. 

3. Greedy algorithms try to find a localized optimum solution, which may eventually lead to globally optimized solutions. However, generally greedy algorithms do not provide globally optimized solutions.

# Krushals Algorithm
It is an algorithm for finding the minimum cost spanning tree of the given graph. In kruskal’s algorithm, edges are added to the spanning tree in increasing order of cost. If the edge E forms a cycle in the spanning, it is discarded.

## Implementation
This algorithm will create spanning tree with minimum weight, from a given weighted graph. 
Begin
Create the edge list of given graph, with their weights.
Sort the edge list according to their weights in ascending order.
Draw all the nodes to create skeleton for spanning tree.
Pick up the edge at the top of the edge list (i.e. edge with minimum weight).
Remove this edge from the edge list.
Connect the vertices in the skeleton with given edge. If by connecting the vertices, a cycle is created in the skeleton, then discard this edge.
Repeat steps 5 to 7, until n-1 edges are added or list of edges is over.
Return 
