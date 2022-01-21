# trees.md

### What is trees?
<details>
<summary>Answer</summary>
A tree usually represents the hierarchy of elements and depicts the relationships between the elements. Trees are considered as one of the largely used facets of data structures.
Every circle represents a node, and every arrow represents the hierarchy. For you to be able to understand the terminology associated with trees.
  
Terminologies used in trees:
<br>
   1.Root: The topmost node of a tree is called the root. There is no edge pointing to it, but one or more than one edge originating from it. Here, A is the root node.
  </br>
  <br>
   2.Parent: Any node which connects to the child. Node which has an edge pointing to some other node. Here, C is the parent of H.
   </br>
   <br>
   3.Child: Any node which is connected to a parent node. Node which has an edge pointing to it from some other node. Here, H is the child of C.
   </br>
   <br>
   4.Siblings: Nodes belonging to the same parent are called siblings of each other. Nodes B, C and D are siblings of each other, since they have the same parent node A.
   </br>
   <br>
   5.Ancestors: Nodes accessible by following up the edges from a child node upwards are called the ancestors of that node. Ancestors are also the parents of the parents of ……        that node. Here, nodes A, C and H are the ancestors of node I.
   </br>
   <br>
   6.Descendants: Nodes accessible by following up the edges from a parent node downwards are called the descendants of that node. Descendants are also the child of the child of      …… that node. Here, nodes H and I are the descendants of node C.
   </br>
   <br>
   7.Leaf/ External Node: Nodes which have no edge originating from it, and have no child attached to it. These nodes cannot be a parent. Here, nodes E, F, G and I are leaf nodes.
   </br>
   <br>
   8.Internal node: Nodes with at least one child. Here, nodes B, D and C are internal nodes.
   </br>
   <br>
   9.Depth: Depth of a node is the number of edges from root to that node. Here, the depth of nodes A, C, H and I are 0, 1, 2 and 3 respectively.
   </br>
   <br>
   10.Height: Height of a node is the number of edges from that node to the deepest leaf. Here, the height of node A is 3, since the deepest leaf from this node is node I. And         similarly, height of node C is 2.
   </br>
</details>

### What is a Binary Tree?

<details>
  <summary>Answer</summary>
  A binary tree is a special type of tree where each node has a degree equal to or less than two which means each node should have at most two children.
<br>  
 1.A tree with n nodes has n-1 Why n-1?
 Because in a tree, there is one and only edge corresponding to all the nodes except the root           node. The root node has no parent, hence no edge pointing to it. Therefore, a total of n-1 edges.
</br>
<br>
2.The degree of a node in a tree is the number of children of a node.
</br>
<br>
3.The degree of a tree is the highest degree of a node among all the nodes present in the tree.
</br>
</details>
  
