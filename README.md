# BFS-using-STL-for-competitive-coding
BFS using STL for competitive coding



A STL based simple implementation of BFS using queue and vector in STL. The adjacency list is represented using vectors of vector.
In BFS, we start with a node.
1) Create a queue and enqueue source into it. 
   Mark source as visited.
2) While queue is not empty, do following
    a) Dequeue a vertex from queue. Let this 
       be f.
    b) Print f
    c) Enqueue all not yet visited adjacent
       of f and mark them visited.





Input:
8 10
0 1
0 2
0 3
0 4
1 5
2 5
3 6
4 6
5 7
6 7

Output:
0 1 2 3 4 5 6 7


       
