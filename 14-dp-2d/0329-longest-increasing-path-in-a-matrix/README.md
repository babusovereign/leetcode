# 329. Longest Increasing Path in a Matrix

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Hard | [2-D Dynamic Programming](../README.md) | [LeetCode 329](https://leetcode.com/problems/longest-increasing-path-in-a-matrix/) |

## Problem

Given an `m` x `n` integer matrix, return the length (in cells) of the longest path in which every step moves up, down, left, or right to a cell with a strictly larger value. Diagonal moves and wrapping around the edges are not allowed.

**Implement:** `def longestIncreasingPath(self, matrix: list[list[int]]) -> int`

## Examples

**Example 1**

```text
Input:  matrix = [[1, 2, 3], [6, 5, 4], [7, 8, 9]]
Output: 9
```

The snake 1-2-3-4-5-6-7-8-9 visits every cell.

**Example 2**

```text
Input:  matrix = [[5, 5], [5, 5]]
Output: 1
```

Edge case: equal neighbors cannot be stepped to, so each path is one cell.

**Example 3**

```text
Input:  matrix = [[3, 4, 5], [3, 2, 6], [2, 2, 1]]
Output: 4
```

e.g. 3-4-5-6 along the top and right edge.

## Constraints

- 1 <= m, n <= 200
- 0 <= matrix[i][j] <= 2^31 - 1

<details>
<summary>Hint (spoiler)</summary>

- Strict increase means the graph has no cycles, so memoized DFS works without a visited set.

</details>

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 329](https://leetcode.com/problems/longest-increasing-path-in-a-matrix/) for the official statement._
