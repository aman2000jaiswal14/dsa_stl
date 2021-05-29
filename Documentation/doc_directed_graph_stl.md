## Graph Data Structure And Algorithms
A Graph is a non-linear data structure consisting of nodes and edges. The nodes are sometimes also referred to as vertices and the edges are lines or arcs that connect any two nodes in the graph. <br>
A Graph consists of a finite set of vertices(or nodes as n) and set of Edges (as e) which connect a pair of nodes.<br>

---
### import 
```
from dsa_stl.directed_graph_stl import DGraph
```
---
### initiate object
```
g = DGraph(n,e)
```
- parameters
  - n : number of vertices
  - e : number of edges

- parameters initiated
  - adj_list : adjacency list of graph
  - edge_list

#### buildGraph
```
g.buildGraph()
```
- inputs
  - take two space seperated input edges between vertices u to v, add only one edge at a time.
   
#### build_dijkstre_graph
```
g.build_dijkstre_graph()
```
- inputs
  - take three space seperated input edges between vertices u to v and c cost on edge for total e deges.


#### dijkstre_sssp
```
g.dijkstre_sssp(i)
```
- find single source shortest path to all other vertices.
- input
  - take i th vertices as source vertices
- output
  - gives a list of n integer contain min cost to reach to all other vertices to the i th source.

#### build_kruskal_graph
#### msp_kruskal
#### buildBellmanford_graph
#### bellmanford_sssp
#### build_Edmand_karp_graph
#### edmand_karp_maxflow
