# topologicalsort-graph-traversal-
Code of directive acyclic graph traversal using topological sort.

Objective - Directive acyclic graph traversal(DFS) so that it can be applied to traverse build systems , Folders traversal , scheduing tasks .

Theory- Topological sort is ordering of vertices of a graph such that for every edge u,v going from u to v , u should always appear 
before v in the ordering.

Implementation - This class(Graph) represents a directed graph using adjacency list representation .
Graph g = new Graph(8); 
		
g.addEdge(0, 2); 
g.addEdge(1, 2); 
g.addEdge(1, 3); 
g.addEdge(2, 4); 
g.addEdge(3, 5); 
g.addEdge(4, 7); 
g.addEdge(4, 5); 
g.addEdge(5, 6);

LinkedList class of Java(Collections) is used for this as in the code.(Graph.java)

Starting from Vertex 0(Source) graph is traversed in DFS manner and the required sequence is stored in a Stack which is the result.

Result -

compile-single:
run-single:
Following is a Topological sort of the given graph
1 3 0 2 4 5 6 7 


