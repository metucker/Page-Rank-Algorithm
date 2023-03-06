# Page-Rank-Algorithm
An simplified implementation of Google's Page Rank Algorithm.

## Documentation

### Functions

#### Brief Description of Methods:

  * InsertPages(): inserts each vertex in a given edge to a map<string, int> so that the string names of the vertices are organized alphabetically and have an associated index

  * GetIndex(): this retrieves the index of a vertex, given its string name

  * InsertEdges(): inserts edge data points into first map

  * OutDegreeRank(): creates a new map based on out degree data from the first map

  * PageRank(): calculates the page rank r(t) of each vertex in the graph

### Implementation

> To implement the graph used for page ranking, I used one map for the names of the vertices and their respective indices (assigned in the order edges are added to the graph).

> I created two nested map structures to store the graph data. The first map structure is used to insert the edges and vertices in the way they are given. The second map structure is created from the first, calculating and storing the outdegrees of the different vertices as weights. 

> For the page rank algorithm, I use two vectors: one to store r(0) and the subsequent r(t), the second vector holds r(t+1) before copying it to the other vector for the next iteration. 

### Source Code
> Please contact me for a private repository link to the source code.
