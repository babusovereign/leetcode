# 97. Interleaving String

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [2-D Dynamic Programming](../README.md) | [LeetCode 97](https://leetcode.com/problems/interleaving-string/) |

## Problem

Given strings `s1`, `s2`, and `s3`, decide whether `s3` can be formed by interleaving `s1` and `s2`: every character of both strings is used exactly once, and each string's characters keep their original relative order in `s3`. Return `true` or `false`.

**Implement:** `def isInterleave(self, s1: str, s2: str, s3: str) -> bool`

## Examples

**Example 1**

```text
Input:  s1 = "ab", s2 = "cd", s3 = "cabd"
Output: true
```

c (s2), a (s1), b (s1), d (s2).

**Example 2**

```text
Input:  s1 = "ab", s2 = "cd", s3 = "abdc"
Output: false
```

"d" appears before "c", breaking s2's order.

**Example 3**

```text
Input:  s1 = "", s2 = "", s3 = ""
Output: true
```

Edge case: all empty.

## Constraints

- 0 <= s1.length, s2.length <= 100
- 0 <= s3.length <= 200
- All strings are lowercase English letters.

## Notes

- If the lengths don't add up, the answer is immediately `false`.
- Follow-up: use only O(s2.length) extra space.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 97](https://leetcode.com/problems/interleaving-string/) for the official statement._
