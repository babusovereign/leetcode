# 200. Number of Islands

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Graphs](../README.md) | [LeetCode 200](https://leetcode.com/problems/number-of-islands/) |

## Problem

You are given an `m x n` grid of characters where `'1'` is land and `'0'` is water. An island is a group of land cells connected horizontally or vertically (not diagonally), and everything outside the grid counts as water. Return the number of islands.

**Implement:** `int numIslands(char[][] grid)`

## Examples

**Example 1**

```text
Input:  grid = [["1", "0", "1", "1"], ["1", "0", "0", "1"], ["0", "1", "0", "0"], ["0", "0", "0", "1"]]
Output: 4
```

Islands: the two cells in column 0, the L-shape at the top right, the lone cell at (2,1), and the lone cell at (3,3). Diagonal contact does not connect.

**Example 2**

```text
Input:  grid = [["0", "0"], ["0", "0"]]
Output: 0
```

**Example 3**

```text
Input:  grid = [["1", "1", "1"], ["0", "1", "0"], ["1", "1", "1"]]
Output: 1
```

## Constraints

- 1 <= m, n <= 300
- Each cell is `'0'` or `'1'`.

## Notes

- Is it okay to modify the grid in place to mark visited cells?

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 200](https://leetcode.com/problems/number-of-islands/) for the official statement._
