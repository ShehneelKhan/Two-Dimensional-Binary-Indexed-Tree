# 2D Fenwick Tree
This is the project for "Data structures and algorithms".
I have used Python for this project whereas no libraries have been used.


## Introduction

To understand 2D Fenwick tree better, you should first understand Fenwick tree.
### Binary Indexed Tree/Fenwick Tree
A Binary Indexed Tree or Fenwick Tree is a data structure that can efficiently update elements and calculate prefix sums in a table of numbers. We know that to answer range sum queries on a 1-D array efficiently, binary indexed tree (or Fenwick Tree) is the best choice (even better than segment tree due to less memory requirements and a little faster than segment tree).

### Two Dimenstional Binary Indexed Tree/2D Fenwick Tree
2D Fenwick tree is one such implementation used to answer sub-matrix queries, i.e. queries in 2 dimensions. Fenwick tree is considered a prerequisite to understand 2D Fenwick tree. Like 1D, 2D Fenwick tree also requires the operation to be invertible.

Since Fenwick tree stores prefix sums, 1D Fenwick tree works by processing query(m, n) as query(1, n) - query(1, m - 1). 2D Fenwick tree operates on a matrix, so query is processed differently, but the requirement is still same, i.e. operation must be invertible.

## Complexity
### Space complexity : O(MN)

### Worst case time complexities:

* Update : O(log2(MN))
* Query : O(log2(MN))
Where the matrix is of size M x N


## Applications
* Is much more space efficient than 2D Segment tree or Quad tree.
* The queries can be processed in O(log2mn) time.
* Used for finding sub-matrix sum/product etc.
* Cannot be used for sub-matrix min/max.
