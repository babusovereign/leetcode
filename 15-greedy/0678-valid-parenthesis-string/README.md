# 678. Valid Parenthesis String

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Greedy](../README.md) | [LeetCode 678](https://leetcode.com/problems/valid-parenthesis-string/) |

## Problem

You are given a string `s` made only of `'('`, `')'` and `'*'`. Each `'*'` is a wildcard that can act as `'('`, as `')'`, or as an empty string.

Return `true` if some choice of replacements makes `s` a balanced parenthesis string (every `'('` closed by a later `')'`, and no `')'` without a matching earlier `'('`). The empty string counts as balanced.

**Implement:** `def checkValidString(self, s: str) -> bool`

## Examples

**Example 1**

```text
Input:  s = "(*))"
Output: true
```

Treat `*` as `(` to get `(())`.

**Example 2**

```text
Input:  s = "*)("
Output: false
```

The final `(` has nothing after it to close it.

**Example 3**

```text
Input:  s = "((*"
Output: false
```

Two opens but at most one possible close.

**Example 4**

```text
Input:  s = "**"
Output: true
```

Both stars can be empty, or `()`.

## Constraints

- 1 <= s.length <= 100
- s[i] is '(', ')' or '*'.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 678](https://leetcode.com/problems/valid-parenthesis-string/) for the official statement._
