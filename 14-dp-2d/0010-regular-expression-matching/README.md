# 10. Regular Expression Matching

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Hard | [2-D Dynamic Programming](../README.md) | [LeetCode 10](https://leetcode.com/problems/regular-expression-matching/) |

## Problem

Implement regular-expression matching for a string `s` and a pattern `p` supporting two special characters: `.` matches any single character, and `*` matches zero or more copies of the character just before it. The pattern must match the whole string, not just part of it. Return `true` or `false`.

**Implement:** `def isMatch(self, s: str, p: str) -> bool`

## Examples

**Example 1**

```text
Input:  s = "abc", p = "a.c"
Output: true
```

`.` stands in for "b".

**Example 2**

```text
Input:  s = "b", p = "a*b"
Output: true
```

`a*` matches zero "a"s.

**Example 3**

```text
Input:  s = "ab", p = ".*c"
Output: false
```

The pattern requires a final "c".

## Constraints

- 1 <= s.length <= 20
- 1 <= p.length <= 20
- `s` has only lowercase letters; `p` has only lowercase letters, `.`, and `*`.
- Every `*` is preceded by a valid character.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 10](https://leetcode.com/problems/regular-expression-matching/) for the official statement._
