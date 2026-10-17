# 20. Valid Parentheses

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Easy | [Stack](../README.md) | [LeetCode 20](https://leetcode.com/problems/valid-parentheses/) |

## Problem

Given a string `s` made up only of the bracket characters `(`, `)`, `[`, `]`, `{`, `}`, return `true` if the brackets are properly balanced: every opening bracket is closed by a bracket of the same type, closings happen in the reverse order of openings (correct nesting), and no closing bracket appears without a matching opener.

**Implement:** `def isValid(self, s: str) -> bool`

## Examples

**Example 1**

```text
Input:  s = "{[()()]}"
Output: true
```

**Example 2**

```text
Input:  s = "([)]"
Output: false
```

The `)` tries to close `(` while `[` is still open.

**Example 3**

```text
Input:  s = "(("
Output: false
```

Openers left unclosed.

## Constraints

- 1 <= s.length <= 10^4
- `s` contains only `()[]{}`.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 20](https://leetcode.com/problems/valid-parentheses/) for the official statement._
