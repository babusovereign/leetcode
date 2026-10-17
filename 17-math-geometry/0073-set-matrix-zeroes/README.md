# 73. Set Matrix Zeroes

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Math & Geometry](../README.md) | [LeetCode 73](https://leetcode.com/problems/set-matrix-zeroes/) |

## Problem

Given an `m x n` integer matrix, whenever a cell contains `0`, set every cell in that cell's entire row and entire column to `0`. Only zeros present in the original matrix trigger this; zeros you write do not cascade.

Modify the matrix in place.

**Implement:** `def setZeroes(self, matrix: list[list[int]]) -> None`

## Examples

**Example 1**

```text
Input:  matrix = [[1, 2, 3], [4, 0, 6], [7, 8, 9]]
Output: [[1, 0, 3], [0, 0, 0], [7, 0, 9]]
```

**Example 2**

```text
Input:  matrix = [[0, 1, 2, 3], [4, 5, 6, 0], [7, 8, 9, 1]]
Output: [[0, 0, 0, 0], [0, 0, 0, 0], [0, 8, 9, 0]]
```

Original zeros at (0, 0) and (1, 3) clear rows 0-1 and columns 0 and 3.

**Example 3**

```text
Input:  matrix = [[5, 6], [7, 8]]
Output: [[5, 6], [7, 8]]
```

No zeros, nothing changes.

## Constraints

- m == matrix.length, n == matrix[0].length
- 1 <= m, n <= 200
- -2^31 <= matrix[i][j] <= 2^31 - 1

## Notes

- Follow-up: O(m + n) extra space is straightforward; can you do it with O(1) extra space?
- Output shows the matrix after the call.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 73](https://leetcode.com/problems/set-matrix-zeroes/) for the official statement._
