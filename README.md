# trees.md

### What is trees?
<details>
<summary>Answer</summary>
A tree usually represents the hierarchy of elements and depicts the relationships between the elements. Trees are considered as one of the largely used facets of data structures.
</details>


<details>
  <summary>Answer</suummary>
![Image_1](https://user-images.githubusercontent.com/81321487/150477215-00bd0493-c5ec-4e46-8c06-b1c0bc23c7d4.jpg)
  
  Every circle represents a node, and every arrow represents the hierarchy. For you to be able to understand the terminology associated with trees.
  Terminologies used in trees:

   1.Root: The topmost node of a tree is called the root. There is no edge pointing to it, but one or more than one edge originating from it. Here, A is the root node.
   2.Parent: Any node which connects to the child. Node which has an edge pointing to some other node. Here, C is the parent of H.
   3.Child: Any node which is connected to a parent node. Node which has an edge pointing to it from some other node. Here, H is the child of C.
   4.Siblings: Nodes belonging to the same parent are called siblings of each other. Nodes B, C and D are siblings of each other, since they have the same parent node A.
   5.Ancestors: Nodes accessible by following up the edges from a child node upwards are called the ancestors of that node. Ancestors are also the parents of the parents of ……        that node. Here, nodes A, C and H are the ancestors of node I.
   6.Descendants: Nodes accessible by following up the edges from a parent node downwards are called the descendants of that node. Descendants are also the child of the child of      …… that node. Here, nodes H and I are the descendants of node C.
   7.Leaf/ External Node: Nodes which have no edge originating from it, and have no child attached to it. These nodes cannot be a parent. Here, nodes E, F, G and I are leaf nodes.
   8.Internal node: Nodes with at least one child. Here, nodes B, D and C are internal nodes.
   9.Depth: Depth of a node is the number of edges from root to that node. Here, the depth of nodes A, C, H and I are 0, 1, 2 and 3 respectively.
   10.Height: Height of a node is the number of edges from that node to the deepest leaf. Here, the height of node A is 3, since the deepest leaf from this node is node I. And         similarly, height of node C is 2.


</details>
