# 763. Partition Labels

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Greedy](../README.md) | [LeetCode 763](https://leetcode.com/problems/partition-labels/) |

## Problem

Given a string `s` of lowercase English letters, cut it into as many contiguous pieces as possible such that every letter appears in at most one piece. Concatenating the pieces in order must give back `s`.

Return a list of the piece lengths, in order.

**Implement:** `def partitionLabels(self, s: str) -> list[int]`

## Examples

**Example 1**

```text
Input:  s = "abacdcdeffe"
Output: [3, 4, 4]
```

Pieces: `"aba"`, `"cdcd"`, `"effe"`.

**Example 2**

```text
Input:  s = "zzzz"
Output: [4]
```

One letter repeated means one piece.

**Example 3**

```text
Input:  s = "abc"
Output: [1, 1, 1]
```

All letters are distinct, so each can stand alone.

## Constraints

- 1 <= s.length <= 500
- s contains only lowercase English letters.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 763](https://leetcode.com/problems/partition-labels/) for the official statement._
