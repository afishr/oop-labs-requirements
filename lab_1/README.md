# Lab 1: Data Structures and Operations on Them

## Intro

Hi there. In this laboratory work we'll dive into incomprehensible yet beautiful world of data structures. And, to spice the things up, you have to implement this laboratory work in **C programming language**.

## General Requirements

* Lab 0 implemented.
* All operations (files and directories creating, compiling source code, creating git repository and committing changes and etc.) should be done **using command line exclusively**.
* All data structures in this laboratory work should be **self-implemented**, i.e. don't use any library that provides them out-of-the-box.

## Tasks: What will you choose?

For this laboratory work, you have two ways of implementing it.

![Matrix: Pills choice scene](img/choice.jpg "What will you choose?")

### Old Fashioned Path

The the **minimal requirement** to gain at least *5 points* is to:
1. Implement one of the data structures from the list below.
1. Add an interactive menu (command line)
1. Add the possibility to load the data structure from a file and display it in the terminal.
1. Add the possibility to input the data structure from keyboard and save it in a file.

Having in mind the minimal conditions, let's see what operations you can additionally implement. \
**Note**: All the operations described below must be able to perform manipulations on data structures loaded from a file and save those changes back.

* **Linked List** (min. *5 points*):
    * Append (*0.5 point*)
    * Prepend (*0.5 point*)
    * Reverse (*0.5 point*)
    * Add a value to the specific index (*0.5 point*)
    * Remove a value the from index (*0.5 point*)
    * Sort the linked list, with re-arranging the cells, not just copying values (*0.5 point*)
    * Search for a value (*0.5 point*)
    * Join two linked lists (*0.5 point*)
    * Backwards traversal, use double-linked-list (*1 point*)
* **Queue** (min. *5 points*):
    * Queue (*0.5 point*)
    * Dequeue (*0.5 point*)
    * Search (*0.5 point*)
    * Sort (*0.5 point*)
    * Reverse (*0.5 point*)
    * Priority queue (*1 point*)
    * Circular queue (*1 point*)
* **Binary Tree** (min. *5 points*):
    * Insert (*0.5 point*)
    * Delete (*0.5 point*)
    * Search (*0.5 point*)
    * In-order traversal (*0.5 point*)
    * Pre-order traversal (*0.5 point*)
    * Post-order traversal (*0.5 point*)
    * Sort, i.e. transform in a binary search tree (*1 point*)
    * Balance, i.e transform in a balanced binary tree (*1 point*)
* **Graph** (min. *5 points*):
    * Insert (*0.5 point*)
    * Delete (*0.5 point*)
    * Search (*0.5 point*)
    * Depth-first traversal (*0.5 point*)
    * Breadth-first traversal (*0.5 point*)
    * Find the path from a vertex to another (*0.5 point*)
    * Find minimum spanning tree (*1 point*)
    * Find the subgraph containing the given vertices (*1 points*)

### A More Interesting Path

On the other hand, you can put those data structures to perform something more interesting than just some abstract operations. You can implement a small command line game.

The minimal requirements to get *6 points* here are: implement either **Tower of Hanoi** or **15 Puzzle**. \
**Important:** this should a be a fully working game with **a menu**, **input handling** and **a visual way to observe the game progress**.

Additional tasks would be:
* Colorful output and clear design (*1 point*)
* Implement files support to provide saving of the game state and option to resume it (*1 point*)
* Restart feature (*1 point*)
* Do/undo feature (*1 point*)

**BONUS:** for receiving *2 extra points* for this laboratory work, implement an algorithm that will solve your game.

## Presentation

Upload your code to a remote repository and send the link to it to <alexandr.calugari@isa.utm.md> with subject including 'OOP Lab 1', **before the deadline**. Once again, use command line to commit and push your changes with Git.

## Deadline

**Time to complete:** _**1 week**_ since you receive the requirements \
_Each week_ of lateness will cost you minus _**1 point**_.

**Good Luck!**

## Useful Links

[Queue Data Structure: Types, Implementation, Applications](https://www.naukri.com/learning/articles/queue-data-structure-types-implementation-applications/)

[Circular Queue](https://www.javatpoint.com/circular-queue)

[Tree Traversals (Inorder, Preorder and Postorder)](https://www.geeksforgeeks.org/tree-traversals-inorder-preorder-and-postorder/)

[Tree Sort](https://www.geeksforgeeks.org/tree-sort/)

[Balanced Binary Tree](https://www.programiz.com/dsa/balanced-binary-tree)

[Complexity of different operations in Binary tree, Binary Search Tree and AVL tree](https://www.geeksforgeeks.org/complexity-different-operations-binary-tree-binary-search-tree-avl-tree/)

[Graphs in Data Structure: Types, Representation, Operations](https://www.naukri.com/learning/articles/graphs-in-data-structure-types-representation-operations/)

[BFS vs. DFS](https://www.javatpoint.com/bfs-vs-dfs)

[Graph Operations and Modifications](https://reference.wolfram.com/language/guide/GraphModifications.html)