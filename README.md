# Binary Trees in C - Project 0x1D

![Author](https://img.shields.io/badge/Author-Azuka%20Uteh-blue.svg)



---

Welcome to the **Binary Trees in C - Project 0x1D**! This project dives into the realm of binary trees using the C programming language. Binary trees are critical data structures with a wide range of applications, from efficient searching to expression parsing.



<p align="center">
  <img src="binary_tree_logo.png" alt="Binary Tree Logo">
</p>



## Table of Contents

- [Project Overview](#project-overview)
- [Project Goals](#project-goals)
- [Key Features](#key-features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Examples](#examples)
- [Requirement](#requirement)
- [Contributing](#contributing)
- [More info](#more-info)
- [License](#license)

## Project Overview

This project is meticulously designed to provide an in-depth understanding of binary trees and their versatile implementations. It encompasses core concepts such as binary search trees (BSTs), tree traversals, balancing techniques, and more. Expect a blend of theoretical insights and hands-on code examples.

## Project Goals

- **Comprehensive Comprehension:** Master the structure and properties of binary trees.
- **Practical Proficiency:** Implement fundamental binary tree operations, including insertion, deletion, and searching.
- **Tree Types:** Explore various binary tree types, with a special focus on binary search trees.
- **Traversal Techniques:** Familiarize yourself with tree traversal algorithms: in-order, pre-order, and post-order.
- **Balancing Know-How:** Delve into the realm of balancing techniques through AVL trees.

## Key Features

- **Rich Explanations:** Clear and comprehensive explanations of binary tree concepts.
- **Code Craftsmanship:** Well-documented C code examples showcasing diverse binary tree operations.
- **Visual Aids:** Visual representations to facilitate understanding of intricate tree structures.
- **Traversal Insights:** Explicit examples of tree traversal algorithms in action.
- **Balancing Demystified:** Detailed exploration of balancing methodologies, featuring AVL trees.

## Getting Started

To embark on this binary tree journey:

1. Clone the repository to your local machine.
2. Navigate to the project directory.

```bash
git clone https://github.com/azukauteh/binary_trees.git
cd binary_trees
```

## Usage

Explore the project files to uncover source code,and visual aids pertaining to binary trees. Each files contains iwith specific instructions and insights.

## Examples

The `examples` file harbors hands-on illustrations of binary tree operations. Each example houses C code that brings distinct binary tree concepts to life. Compile and run these examples to witness the magic unfold.


## Requirements

- Allowed editors: vi, vim, emacs
- All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
- All your files should end with a new line
- Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
- You are not allowed to use global variables
- No more than 5 functions per file
- You are allowed to use the standard library
- The prototypes of all your functions should be included in your header file called binary_trees.h
- All your header files should be include guarded


## Contributing

Contributions are heartily welcomed! Should you possess enhancements, bug fixes, or supplementary examples, please initiate a pull request. Ensure your contributions align with the project's coding standards and guidelines.


## More Info

- Data structures

Basic Binary Tree

/**
 * struct binary_tree_s - Binary tree node
 *
 * @n: Integer stored in the node
 * @parent: Pointer to the parent node
 * @left: Pointer to the left child node
 * @right: Pointer to the right child node
 */
struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;
Binary Search Tree
typedef struct binary_tree_s bst_t;
AVL Tree
typedef struct binary_tree_s avl_t;
Max Binary Heap
typedef struct binary_tree_s heap_t;


## License

This project operates under the wings of the [MIT License](LICENSE).

---
