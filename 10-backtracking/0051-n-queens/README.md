# 51. N-Queens

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Hard | [Backtracking](../README.md) | [LeetCode 51](https://leetcode.com/problems/n-queens/) |

## Problem

Place `n` queens on an `n x n` chessboard so that no two queens attack each other, meaning no two share a row, a column, or a diagonal. Return every distinct valid arrangement. Each arrangement is a list of `n` strings, one per row, where `'Q'` marks a queen and `'.'` marks an empty square; the arrangements may be returned in any order.

**Implement:** `List<List<String>> solveNQueens(int n)`

## Examples

**Example 1**

```text
Input:  n = 4
Output: [[".Q..", "...Q", "Q...", "..Q."], ["..Q.", "Q...", "...Q", ".Q.."]] (any order)
```

Exactly two arrangements exist for a 4x4 board.

**Example 2**

```text
Input:  n = 3
Output: []
```

No valid placement exists for n = 2 or n = 3.

**Example 3**

```text
Input:  n = 1
Output: [["Q"]]
```

## Constraints

- 1 <= n <= 9

## Notes

- A related variant (LeetCode 52) asks only for the number of solutions.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 51](https://leetcode.com/problems/n-queens/) for the official statement._
