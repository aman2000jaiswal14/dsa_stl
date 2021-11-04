## Balance Binary Search Tree
## AVL Tree
AVL tree is a self-balancing Binary Search Tree (BST) where the difference between heights of left and right subtrees cannot be more than one for all nodes.
Most of the BST operations (e.g., search, max, min, insert, delete.. etc) take O(h) time where h is the height of the BST.

### import 
```
from dsa_stl.Balance_bst import AVLTree
from dsa_stl.Balance_bst import BinarySearchTree
```
---
### initiate object
```
avltree = AVLTree()
bst = BinarySearchTree()
```

### insert Node
```
avltree.insert(nodevalue)
bst.insert(nodevalue)
```

### deleteNode
```
avltree.delete(nodevalue)
bst.delete(nodevalue)
```

### printTree
```
avltree.printTree(bfs=False,get=False)
bst.printTree()
```
