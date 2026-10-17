# 74. Search a 2D Matrix

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Binary Search](../README.md) | [LeetCode 74](https://leetcode.com/problems/search-a-2d-matrix/) |

## Problem

You are given an `m x n` integer matrix in which each row is sorted in ascending order and the first value of every row is greater than the last value of the previous row (so reading the rows in order gives one sorted sequence). Given an integer `target`, return `true` if it appears in the matrix and `false` otherwise, in O(log(m * n)) time.

**Implement:** `def searchMatrix(self, matrix: list[list[int]], target: int) -> bool`

## Examples

**Example 1**

```text
Input:  matrix = [[2, 4, 7, 9], [12, 15, 18, 21], [25, 31, 40, 52]], target = 18
Output: true
```

**Example 2**

```text
Input:  matrix = [[2, 4, 7, 9], [12, 15, 18, 21], [25, 31, 40, 52]], target = 10
Output: false
```

`10` would fall between rows 0 and 1.

**Example 3**

```text
Input:  matrix = [[-5]], target = -5
Output: true
```

## Constraints

- 1 <= m, n <= 100
- -10^4 <= matrix[i][j], target <= 10^4

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 74](https://leetcode.com/problems/search-a-2d-matrix/) for the official statement._
