A note for my learning curve about Data structure in Cpp

## Tree.

1. Binary Search Tree: 
- left nodes with key lesser than root's key
- right nodes with key greater than root's key
- the left and right subtree each must also be binary tree

2. AVL Tree:

- self balancing Binary Search Tree.
- different betweek heights of left and right subtrees cannot be more than one for all nodes.

3. B-Tree:

- self balancing tree, allows efficent access, insert, and delete of data items. Commonly used in databases and file systems.
[Refer to this article to read about more on B-Tree](https://www.geeksforgeeks.org/introduction-of-b-tree-2/)

4. B-Tree+:
Variant of the B-tree [Refer to this article to read about more on B+ Tree](https://www.geeksforgeeks.org/introduction-of-b-tree/)

## Tree travesal.
Tree traversal algorithms can be classified into two categories:
1. Depth First Search DFS
2. Breadth First Search BFS

DFS:
Can be further classified into three categories:

    * Preorder Travesal (current-left-right)
    * Inorder Travesal (left-current-right)
    * PostOrder Traversal (left-right-currrent)
BFS:

    * Level order travesal``


