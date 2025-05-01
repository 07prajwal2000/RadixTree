# Radix Tree Implementation for In-Memory Key/Value Store
This repository contains an implementation of a Radix Tree. The Radix Tree is a data structure used for efficient storage and retrieval of strings.

## JavaScript Implementation
- Filename: [radix-tree.js](radixTree.js).
- Implementation specifics:
  - Used Sorted strings to store the key/value pairs.
  - Improved using AVL/Red-Black Trees which are better in terms of time complexity for insertion and deletion.
  - Strings are split (which allocates memory), but it can be improved using pointers. 
- Supports Get/Set/Delete operations.