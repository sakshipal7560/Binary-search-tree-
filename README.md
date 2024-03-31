# Binary-search-tree-
Deletion in a binary search tree involves removing a node while maintaining the binary search tree property. To delete a node:

 1. If the node to be deleted has no children, simply remove it.
 2. If the node has one child, replace the node with its child.
 3.If the node has two children, find its successor (the smallest node in its right subtree), replace the node's value with the successor's value, and recursively delete the successor from the right subtree.
After deletion, ensure that the binary search tree property is maintained by updating the parent pointers accordingly.
