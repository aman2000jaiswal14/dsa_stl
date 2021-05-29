## Lowest Common Ancestor
Let T be a rooted tree. The lowest common ancestor between two nodes n1 and n2 is defined as the lowest node in T that has both n1 and n2 as descendants <br>

---
### import 
```
from dsa_stl.lca_graph_stl import LCA
```
---

### initiate object
```
lca = LCA(n,e)
```
- parameters
  - n : number of vertices
  - e : number of edges

- parameters initiated
  - adj_list : adjacency list of graph


#### addEdge
```
lca.addEdge(u,v)
```
- add edge between u to v and v to u in tree

#### buildTree

#### dfs_level_parent

#### lcaNaive
```
lca.lcaNaive(u,v,level,parent)
```
#### binary_lifting
```
lca.binary_lifting(parent,max_level)
```
#### lcaFast
```
lca.lcaFast(u, v, level, parent)
```
#### distance_between_2_node
```
lca.distance_between_2_node(u,v)
```
- return distance between 2 node
