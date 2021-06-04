# Trees
Tree is a non linear data structures where nodes are connected to each other through links.

## Binary Tree
Binary Tree is a special datastructure used for data storage purposes. A binary tree has a special condition that each node can have a maximum of two children. A binary tree has the benefits of both an ordered array and a linked list as search is as quick as in a sorted array and insertion or deletion operation are as fast as in linked list.

## Binary Search Tree
A Binary Search Tree (BST) is a tree in which all the nodes follow the below-mentioned properties −

1. The value of the key of the left sub-tree is less than the value of its parent (root) node's key.

2. The value of the key of the right sub-tree is greater than or equal to the value of its parent (root) node's key.

Thus, BST divides all its sub-trees into two segments; the left sub-tree and the right sub-tree and can be defined as
left_subtree (keys) < node (key) ≤ right_subtree (keys)

BST is a collection of nodes arranged in a way where they maintain BST properties. Each node has a key and an associated value. While searching, the desired key is compared to the keys in BST and if found, the associated value is retrieved.

### Code includes -
1. insertion
2. deletion with 3 cases (node with no child, node with one child, node with both left & right children)
3. Inorder traversal
4. preorder traversal
5. postorder traversal
6. levelorder traversal
7. search
8. height of the tree
9. number of nodes in tree
