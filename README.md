# Network-Shortest-Paths
Shortest paths in a network with weighted edges.

Files included:
1. Graph.java 
1. Network.txt - Input File

Language used to implement the algorithm is Java 

JRE Version 1.8

Naming is done according to standard java naming convention.

### Program Design

The program takes an input file and presents the user with a menu. User can choose either to :

* Print all vertices with their vertices.
* Print shortest path between 2 vertices.
* Print reachable vertices from each vertex. 
* Add an edge 
* Delete an edge 
* Mark an edge or a Vertex as Down or Up

#### Datastructures used are:

* ArrayLists to store paths, vertices, edges .
* LinkedLsts to store ordered lists of vertices, adjacent vertices.
* HashMap to store vertices.
* Hashset to store sets of vertices.


### Execution Instructions

`javac Graph.java`

`java Graph <filename>` 
Eg. java Network.txt

where filename is the file containing the graph.

### Reachable Algo Analysis

We call a method reachable for each vertex V which recursively visits adjacent vertices V and stores in a list. So, we get a list of reachble vertices for all vertices. This should take O(v^2) time . 
