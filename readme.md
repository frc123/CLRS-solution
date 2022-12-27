# [CLRS](https://github.com/yirong-c/CLRS)

This repo includes 

- C++ code implementation of data structures and algorithms

- exercise and problem solutions of "Introduction to Algorithms" (CLRS) 3rd edition 
(in LaTeX and handwriting)
(the handwriting part will be updated to LaTeX)

If you have any issues or want to discuss anything,
you are welcome to new an issue or discussion.

For those who starred the repo, we really appreciate it.
Your star is our motivation to do better.

## Solution Menu

Chapter 2 - 11 Contents are Uploading and Migrating
(you can check out codes in [this repo](https://github.com/yirong-c/CLRS-code-solution) for temporary)

| Chapter | Code | Solution |
| --- | --- | --- |
| Chpater 2 - 11 | [Code](https://github.com/yirong-c/CLRS-code-solution) | |
| Chpater 12 (Binary Search Trees) | [Code](https://github.com/yirong-c/CLRS/tree/master/ch12/code) |[Solution](https://github.com/yirong-c/CLRS/tree/master/ch12/solution) (Hand-writing)
| Chpater 13 (Red-Black Trees) | [Code](https://github.com/yirong-c/CLRS/tree/master/ch13/code) | [Solution](https://github.com/yirong-c/CLRS/tree/master/ch13/solution) (Hand-writing)
| Chpater 14 (Augmenting Data Structures) | [Code](https://github.com/yirong-c/CLRS/tree/master/ch14/code) | [Solution](https://github.com/yirong-c/CLRS/blob/master/ch14/solution/ch14.pdf) (LaTeX)
| Chpater 15 (Dynamic Programming) | [Code](https://github.com/yirong-c/CLRS/tree/master/ch15/code) | [Solution](https://github.com/yirong-c/CLRS/blob/master/ch15/solution/ch15.pdf) (LaTeX)
| Chpater 16 (Greedy Algorithms) | [Code](https://github.com/yirong-c/CLRS/tree/master/ch16/code) | [Solution](https://github.com/yirong-c/CLRS/blob/master/ch16/solution/ch16.pdf) (LaTeX)
| Chpater 17 (Amortized Analysis) | [Code](https://github.com/yirong-c/CLRS/tree/master/ch17/code) | [Solution](https://github.com/yirong-c/CLRS/blob/master/ch17/solution/ch17.pdf) (LaTeX)
| Chpater 21 (Data Structures for Disjoint Sets) | [Code](https://github.com/yirong-c/CLRS/tree/master/ch21/code) | [Solution](https://github.com/yirong-c/CLRS/blob/master/ch21/solution/ch21.pdf) (LaTeX)
| Chpater 22 (Elementary Graph Algorithms) | [Code](https://github.com/yirong-c/CLRS/tree/master/ch22/code) | [Solution](https://github.com/yirong-c/CLRS/blob/master/ch22/solution/ch22.pdf) (LaTeX)

## Submodules of the Project

### [Common Operation Template Library (COTL)](https://github.com/yirong-c/common-operation-template-library)

Augmented data structures and algorithms in a style similar to STL
such as partition, selection in linear time, etc.
(widely used in this project) (in the namespace of `cotl`)

### [Matrix](https://github.com/yirong-c/matrix)

Matrix library that supports operator overloading and Strassen's algorithm.

### [Red-Black Trees](https://github.com/yirong-c/red-black-tree)

Basic STL style red-black trees.

### [Persistent Red-Black Trees](https://github.com/yirong-c/persistent-red-black-tree)

- Red-black trees
that maintain past versions of a red-black tree.

- Guarantee O(lg n) running time and space
per selection insertion, or deletion.

### [Order Statistics Trees + Interval Trees](https://github.com/yirong-c/augment-red-black-tree)

- Order Statistics Trees: Red-black trees
that support computation of the rank of an elements in O(lg n).

- Interval Trees: Red-black trees
that support operations on intervals.

## Other Data Structures

### [Elementary Data Structures](https://github.com/yirong-c/CLRS-code-solution/tree/master/src/ch10)

- [Stack + Queue](https://github.com/yirong-c/CLRS-code-solution/blob/master/src/ch10/stack_queue.h)

- [Linked List](https://github.com/yirong-c/CLRS-code-solution/blob/master/src/ch10/linked_list.h)

- [Free List](https://github.com/yirong-c/CLRS-code-solution/blob/master/src/ch10/pointer_object.cpp): 
[header](https://github.com/yirong-c/CLRS-code-solution/blob/master/src/ch10/pointer_object.h)
|
[source](https://github.com/yirong-c/CLRS-code-solution/blob/master/src/ch10/pointer_object.cpp)

- [Rooted Tree](https://github.com/yirong-c/CLRS-code-solution/blob/master/src/ch10/rooted_tree.h)

### [Hash Table](https://github.com/yirong-c/CLRS-code-solution/tree/master/src/ch11)

- [Chained Hash](https://github.com/yirong-c/CLRS-code-solution/blob/master/src/ch11/chained_hash.hpp)

- [Open Addressing](https://github.com/yirong-c/CLRS-code-solution/blob/master/src/ch11/open_addressing.hpp)

### [Disjoint Sets](https://github.com/yirong-c/CLRS/tree/master/ch21/code)

- [Linked-list Representation](https://github.com/yirong-c/CLRS/tree/master/ch21/code/list_representation_of_disjoint_sets.cpp)

- [Disjoint-set Forests](https://github.com/yirong-c/CLRS/tree/master/ch21/code/disjoint_set_forests.cpp)

## More Code Implementation in C++

https://github.com/yirong-c/CLRS-code-solution

This repo includes contents of **Chapter 2 - 11**.

All contents in this repo will be migrated here later.

Solutions will be updated in LaTeX later also.

## Contribute

If you find any errors, other approaches to solution, 
or want to contribute,
you are welcome to create a Pull Request.

Thank you so much for your contribution!

## Bibliography

Cormen, T. H., Leiserson, C. E., Rivest, R. L., & Stein, C. (2009). Introduction to algorithms  (Third edition.). MIT Press.
