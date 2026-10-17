# 261. Graph Valid Tree

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Graphs](../README.md) | [LeetCode 261](https://leetcode.com/problems/graph-valid-tree/) (Premium) |

> LeetCode Premium. The same problem is free to practise on [NeetCode](https://neetcode.io/practice).

## Problem

You are given `n` nodes labelled `0` to `n - 1` and a list of undirected `edges`, where `edges[i] = [a, b]` connects nodes `a` and `b`. Return `true` if these edges form a valid tree: all `n` nodes are connected and there are no cycles. Otherwise return `false`.

**Implement:** `boolean validTree(int n, int[][] edges)`

## Examples

**Example 1**

```text
Input:  n = 5, edges = [[0, 1], [1, 2], [1, 3], [3, 4]]
Output: true
```

**Example 2**

```text
Input:  n = 4, edges = [[0, 1], [1, 2], [2, 0]]
Output: false
```

Nodes 0, 1, 2 form a cycle and node 3 is disconnected.

**Example 3**

```text
Input:  n = 1, edges = []
Output: true
```

A single node with no edges is a valid tree.

## Constraints

- 1 <= n <= 2000
- No duplicate edges and no self-loops.

## Notes

- A tree on `n` nodes has exactly `n - 1` edges; that plus connectivity (or plus acyclicity) is sufficient.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 261](https://leetcode.com/problems/graph-valid-tree/) for the official statement._
