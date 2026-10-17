# 36. Valid Sudoku

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Arrays & Hashing](../README.md) | [LeetCode 36](https://leetcode.com/problems/valid-sudoku/) |

## Problem

Given a 9x9 Sudoku grid in which some cells are filled with digits `'1'`-`'9'` and the rest hold `'.'`, determine whether the filled cells are consistent with the Sudoku rules: no digit may repeat within any row, any column, or any of the nine 3x3 sub-boxes. Only the filled cells are checked; the board does not need to be solvable.

**Implement:** `def isValidSudoku(self, board: list[list[str]]) -> bool`

## Examples

**Example 1**

```text
Input:  board =
[
  ["2", ".", ".", "9", ".", ".", ".", ".", "7"],
  [".", "4", ".", ".", ".", ".", "1", ".", "."],
  [".", ".", "1", ".", "3", ".", ".", ".", "."],
  [".", ".", ".", ".", "8", ".", "5", ".", "."],
  ["3", ".", ".", ".", ".", ".", ".", ".", "6"],
  [".", ".", "7", ".", "5", ".", ".", ".", "."],
  [".", ".", ".", ".", "6", ".", "4", ".", "."],
  [".", ".", "2", ".", ".", ".", ".", "8", "."],
  ["6", ".", ".", ".", ".", "1", ".", ".", "3"]
]
Output: true
```

No row, column, or 3x3 box contains a repeated digit.

**Example 2**

```text
Input:  Same board as above, but with `board[2][0] = '4'`
Output: false
```

The top-left 3x3 box would then contain `'4'` twice (at `[1][1]` and `[2][0]`).

**Example 3**

```text
Input:  Same board as the first example, but with `board[8][4] = '5'`
Output: false
```

Column 4 would then contain `'5'` twice (rows 5 and 8).

## Constraints

- `board` is exactly 9 x 9.
- Each cell is a digit `'1'`-`'9'` or `'.'`.

## Notes

- A board that passes this check might still have no solution; solvability is not part of the question.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 36](https://leetcode.com/problems/valid-sudoku/) for the official statement._
