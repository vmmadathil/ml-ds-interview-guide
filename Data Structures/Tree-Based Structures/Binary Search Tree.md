# Binary Search Trees

Binary search trees are essentiallt "linked lists" with two pointers per node -- a left pointer and a right pointer -- to give fast access to two elements.  There will be a root node, which branches out to left and right subtrees. For it to be a *search* tree, the left subtree keys will be < x, while the right subtree keys will be > x, where x is node. 

## Common Operations

### Searching in a tree
Pretty intuitive -- recursively proceed either left or right depending on whether *x* occurs before or after the root key.

### Finding Minimum and Maximum
The smallest key must be in the left subtree and must be the left-most descendant of the root. Conversely, the largest key must be in the right subtree and must be the right-most descendant of the root.

### Traversal in a Tree
In order traversal can be done recursively processing the left subtree and then right subtree.

### Insertion in a Tree
Must search the tree first for the optimal place and then insert

### Deletion from a Tree
Trickier than insertion. Must link the two descendant subtrees back into the tree.