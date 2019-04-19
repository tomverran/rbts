![Red Black Tree SVG](https://upload.wikimedia.org/wikipedia/commons/1/10/Red-black_tree_example_nN.svg)

[![Test Badge](https://pallas.txk.ch/nalply/rbts/badge?branch=master)](https://pallas.txk.ch/nalply/rbts/)

---

# A red-black tree implementation in Typescript

A red-black tree is a datastructure for sorted storage of key-value pairs.
Items are stored in tree nodes and sorted after a criterium (`LessOp`).
Search, insertion, deletion and traversal are performed in $O(\log n)$ time.
This implementation has the same interface as JavaScript's built-in type
`Map`, so it can be used as replacement for `Map`.

Currently this module does not work correctly. There's a bug with deletion
of nodes. Also, no guarantees of efficiency are given. I suspect, for example,
that the `less` parameter is not good for performance.
