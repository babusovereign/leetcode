# 994. Rotting Oranges

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Graphs](../README.md) | [LeetCode 994](https://leetcode.com/problems/rotting-oranges/) |

## Problem

In an `m x n` grid each cell is `0` (empty), `1` (fresh orange), or `2` (rotten orange). Every minute, each fresh orange that is 4-directionally adjacent to a rotten orange becomes rotten. Return the minimum number of minutes until no fresh orange remains, or `-1` if some fresh orange can never rot.

**Implement:** `int orangesRotting(int[][] grid)`

## Examples

**Example 1**

```text
Input:  grid = [[2, 1, 0], [1, 1, 0], [0, 1, 1]]
Output: 4
```

The rot spreads outward one step per minute; the bottom-right orange is the last to rot.

**Example 2**

```text
Input:  grid = [[1, 0, 2]]
Output: -1
```

The fresh orange is separated from the rotten one by an empty cell, so it never rots.

**Example 3**

```text
Input:  grid = [[0, 0]]
Output: 0
```

There are no fresh oranges, so no time is needed.

## Constraints

- 1 <= m, n <= 10
- Each cell is `0`, `1`, or `2`.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 994](https://leetcode.com/problems/rotting-oranges/) for the official statement._
