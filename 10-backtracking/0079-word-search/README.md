# 79. Word Search

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Backtracking](../README.md) | [LeetCode 79](https://leetcode.com/problems/word-search/) |

## Problem

Given an `m x n` grid of letters `board` and a string `word`, return `true` if `word` can be traced through the grid. A trace starts at any cell and moves to horizontally or vertically adjacent cells (no diagonals), matching the word's letters in order, and no cell may be used more than once in a single trace.

**Implement:** `boolean exist(char[][] board, String word)`

## Examples

**Example 1**

```text
Input:  board = [["C", "A", "T"], ["X", "R", "S"], ["D", "O", "G"]], word = "CARS"
Output: true
```

C(0,0) -> A(0,1) -> R(1,1) -> S(1,2).

**Example 2**

```text
Input:  board = [["C", "A", "T"], ["X", "R", "S"], ["D", "O", "G"]], word = "CAC"
Output: false
```

The path would have to reuse the C cell.

**Example 3**

```text
Input:  board = [["C", "A", "T"], ["X", "R", "S"], ["D", "O", "G"]], word = "TSG"
Output: true
```

Moves are vertical: T(0,2) -> S(1,2) -> G(2,2).

## Constraints

- 1 <= m, n <= 6
- 1 <= word.length <= 15
- `board` and `word` contain only English letters (upper and lower case).

## Notes

- Follow-up: what pruning helps on larger boards (e.g. letter-count checks)?

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 79](https://leetcode.com/problems/word-search/) for the official statement._
