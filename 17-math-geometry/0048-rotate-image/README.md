# 48. Rotate Image

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Math & Geometry](../README.md) | [LeetCode 48](https://leetcode.com/problems/rotate-image/) |

## Problem

You are given an `n x n` matrix. Rotate it 90 degrees clockwise.

The rotation must be done in place: modify the input matrix directly rather than allocating a second matrix.

**Implement:** `def rotate(self, matrix: list[list[int]]) -> None`

## Examples

**Example 1**

```text
Input:  matrix = [[1, 2], [3, 4]]
Output: [[3, 1], [4, 2]]
```

**Example 2**

```text
Input:  matrix = [[1, 2, 3], [4, 5, 6], [7, 8, 9]]
Output: [[7, 4, 1], [8, 5, 2], [9, 6, 3]]
```

The first column, read bottom to top, becomes the first row.

**Example 3**

```text
Input:  matrix = [[7]]
Output: [[7]]
```

## Constraints

- n == matrix.length == matrix[i].length
- 1 <= n <= 20
- -1000 <= matrix[i][j] <= 1000

## Notes

- Output shows the matrix after the call; the function itself returns nothing.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 48](https://leetcode.com/problems/rotate-image/) for the official statement._
