## Graph Data Structure And Algorithms
A Graph is a non-linear data structure consisting of nodes and edges. The nodes are sometimes also referred to as vertices and the edges are lines or arcs that connect any two nodes in the graph. <br>
A Graph consists of a finite set of vertices(or nodes as n) and set of Edges (as e) which connect a pair of nodes.<br>

---
### import 
```
from dsa_stl.graph_stl import Graph
```
---

### initiate object
```
g = Graph(n,e)
```
- parameters
  - n : number of vertices
  - e : number of edges

- parameters initiated
  - adj_list : adjacency list of graph

#### build_adjList
```
g.build_adjList(directed = False,indexed = 1)
```

- parameters
  - directed : whether graph is directed or not (True means directed, default is False) 
  - indexed : whether indexing is 0 based or 1 based (default is 1 based indexing)
- inputs
  - take two space seperated input edges between vertices u and v for total e deges.
 
#### dfs_one
```
g.dfs_one(i)
```
i is the ith vertices to start dfs.
- Output
  - return list of node traversed in order of dfs.

#### bfs_one
```
g.bfs_one(i)
```

#### find_number_of_connected_components
```
g.find_number_of_connected_components()
```
- Output
  - return single integer number of connected components in graph

#### single_source_shortest_path
```
g.single_source_shortest_path(i)
```

#### isTree
```
g.isTree()
```
- return True if graph is tree else False

#### isBipartite
```
g.isBipartite()
```
- return True if graph is bipartite else False

#### isCycle
```
g.isCycle()
```
- return True if graph has cycle else False

#### in_and_out
#### diameter
#### findBridges
#### findArticulation_vertex
#### build_directed_graph_with_indegree
#### topologicalsort
