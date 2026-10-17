# 323. Number of Connected Components in an Undirected Graph

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Graphs](../README.md) | [LeetCode 323](https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/) (Premium) |

> LeetCode Premium. The same problem is free to practise on [NeetCode](https://neetcode.io/practice).

## Problem

Given `n` nodes labelled `0` to `n - 1` and a list of undirected `edges` (each `[a, b]` joins `a` and `b`), return the number of connected components in the graph. Isolated nodes count as their own component.

**Implement:** `int countComponents(int n, int[][] edges)`

## Examples

**Example 1**

```text
Input:  n = 6, edges = [[0, 1], [1, 2], [3, 4]]
Output: 3
```

Components: {0, 1, 2}, {3, 4}, and the isolated node {5}.

**Example 2**

```text
Input:  n = 3, edges = [[0, 1], [1, 2], [2, 0]]
Output: 1
```

A cycle is still a single component.

**Example 3**

```text
Input:  n = 4, edges = []
Output: 4
```

With no edges every node is its own component.

## Constraints

- 1 <= n <= 2000
- No repeated edges and no self-loops.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 323](https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/) for the official statement._
