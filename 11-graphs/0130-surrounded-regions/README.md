# 130. Surrounded Regions

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Graphs](../README.md) | [LeetCode 130](https://leetcode.com/problems/surrounded-regions/) |

## Problem

You are given an `m x n` board of `'X'` and `'O'` characters. A region is a group of `'O'` cells connected horizontally or vertically. A region is captured if none of its cells lies on the board's border; capture it by changing all of its cells to `'X'` in place. Regions that touch the border, directly or through connected `'O'` cells, are left unchanged.

**Implement:** `void solve(char[][] board)`

## Examples

**Example 1**

```text
Input:  board = [["X", "X", "X", "X"], ["X", "O", "O", "X"], ["X", "X", "O", "X"], ["X", "O", "X", "X"]]
Output: [["X", "X", "X", "X"], ["X", "X", "X", "X"], ["X", "X", "X", "X"], ["X", "O", "X", "X"]]
```

The three connected O cells in the middle are enclosed and get flipped; the O on the bottom edge survives.

**Example 2**

```text
Input:  board = [["O", "X"], ["X", "O"]]
Output: [["O", "X"], ["X", "O"]]
```

Every O touches the border, so nothing changes.

## Constraints

- 1 <= m, n <= 200
- Each cell is `'X'` or `'O'`.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 130](https://leetcode.com/problems/surrounded-regions/) for the official statement._
