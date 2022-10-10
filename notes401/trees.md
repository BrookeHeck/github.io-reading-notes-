# Trees
[Reading Notes Link](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/Trees.html)

## Common Terminology
- Node - A Tree node is a component which may contain its own values, and references to other nodes
- Root - The root is the node at the beginning of the tree
- K - A number that specifies the maximum number of children any node may have in a k-ary tree. In a binary tree, k = 2.
- Left - A reference to one child node, in a binary tree
- Right - A reference to the other child node, in a binary tree
- Edge - The edge in a tree is the link between a parent and child node
- Leaf - A leaf is a node that does not have any children
- Height - The height of a tree is the number of edges from the root to the furthest leaf

## Traversals
- Two types of traversals
  - breadth first and depth first
  - Depth first
    - pre-order: root > left > right
    - in-order: left > root > right
    - post-order: left > right > right

  - Pre-order algorithm
  ```
  ALGORITHM preOrder(root)

  OUTPUT <-- root.value

  if root.left is not NULL
      preOrder(root.left)

  if root.right is not NULL
      preOrder(root.right)
  ```

  - Post-order algorithm 
  ```
  ALGORITHM inOrder(root)
  // INPUT <-- root node
  // OUTPUT <-- in-order output of tree node's values

    if root.left is not NULL
        inOrder(root.left)

    OUTPUT <-- root.value

    if root.right is not NULL
        inOrder(root.right)
  ```

  - Post-order algorithm
  ```
  ALGORITHM postOrder(root)
  // INPUT <-- root node
  // OUTPUT <-- post-order output of tree node's values

    if root.left is not NULL
        postOrder(root.left)

    if root.right is not NULL
        postOrder(root.right)

    OUTPUT <-- root.value
  ```

  - Breadth first search algorithm
  ```
  ALGORITHM breadthFirst(root)
  // INPUT  <-- root node
  // OUTPUT <-- front node of queue to console

  Queue breadth <-- new Queue()
  breadth.enqueue(root)

  while ! breadth.is_empty()
    node front = breadth.dequeue()
    OUTPUT <-- front.value

    if front.left is not NULL
      breadth.enqueue(front.left)

    if front.right is not NULL
      breadth.enqueue(front.right)
  ```

## Binary vs K-ary Trees
- Binary trees have nodes with two or less children
- K-ary trees have nodes with k or less nodes
- Traversing a k-ary tree is similar to traversing binary trees, but instead of checking left or right nodes, you have to check nodes up to k.
