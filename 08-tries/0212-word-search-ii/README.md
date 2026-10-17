# 212. Word Search II

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Hard | [Tries](../README.md) | [LeetCode 212](https://leetcode.com/problems/word-search-ii/) |

## Problem

Given an `m x n` grid `board` of lowercase letters and a list of distinct `words`, return every word that can be traced on the board. A word is traced by moving between horizontally or vertically adjacent cells, and the same cell may not be used twice within a single word.

The answer may be returned in any order.

**Implement:** `def findWords(self, board: list[list[str]], words: list[str]) -> list[str]`

## Examples

**Example 1**

```text
Input:  board = [["s", "t", "a", "r"], ["e", "o", "n", "e"], ["a", "p", "t", "s"]],
words = ["star", "stone", "tons", "seat", "pots", "rent"]
Output: ["star", "stone", "pots", "rent"]
```

**Example 2**

```text
Input:  board = [["q", "z"], ["x", "y"]],
words = ["qzy", "qq", "zyxq"]
Output: ["qzy", "zyxq"]
```

`qq` would require reusing the single `q` cell.

**Example 3**

```text
Input:  board = [["k"]],
words = ["k", "kk"]
Output: ["k"]
```

## Constraints

- `1 <= m, n <= 12`
- `1 <= words.length <= 3 * 10^4`
- `1 <= words[i].length <= 10`
- `board` and `words` contain only lowercase English letters.
- All entries of `words` are distinct.

## Notes

- Outputs may be in any order.

<details>
<summary>Hint (spoiler)</summary>

- Running Word Search I once per word is too slow; build a trie of `words` and do one DFS from each cell, pruning trie branches once their words are found.

</details>

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 212](https://leetcode.com/problems/word-search-ii/) for the official statement._
