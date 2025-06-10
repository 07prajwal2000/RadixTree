# Radix Tree Implementation for In-Memory Key/Value Store
This repository contains an implementation of a Radix Tree. The Radix Tree is a data structure used for efficient storage and retrieval of strings.

## JavaScript Implementation
- Filename: [radix-tree.js](radixTree.js).
- Implementation specifics:
  - Used Sorted strings to store the key/value pairs.
  - Strings are split (which allocates memory), but it can be improved using RefStrings (which are not possible in js, but can be cheated using char[]). 
- Supports Get/Set/Delete operations.
