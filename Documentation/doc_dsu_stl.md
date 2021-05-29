## DISJOINT SET DATA STRUCTURE
A disjoint-set data structure is a data structure that keeps track of a set of elements partitioned into a number of disjoint (non-overlapping) subsets. A union-find algorithm is an algorithm that performs two useful operations on such a data structure:<br>
- Find: Determine which subset a particular element is in. This can be used for determining if two elements are in the same subset.<br>
- Union: Join two subsets into a single subset.

---
## Uses
Union-Find Algorithm can be used to check whether an undirected graph contains cycle or not.

---
### import 
```
from dsa_stl.dsu_stl import DSU
```
---
### initiate object
```
dsu = DSU(n)
```
n = number of element in set.

---
#### find
- A utility function to find the subset of an element.
- (uses path compression technique)
```
dsu = DSU(n)
dsu.find(i)
```
##### Output
`
find the subset of i th  element.
`

---
#### union

- A utility function to do union of two subsets

```
dsu = DSU(n)
dsu.union(u,v)
```
---
#### union_by_rank
- A function that does union of two sets of u and v(uses union by rank)
- improved to O(Logn) using Union by Rank 
```
dsu = DSU(n)
dsu.union_by_rank(u,v)
```
