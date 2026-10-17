# 76. Minimum Window Substring

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Hard | [Sliding Window](../README.md) | [LeetCode 76](https://leetcode.com/problems/minimum-window-substring/) |

## Problem

Given strings `s` and `t`, return the shortest contiguous substring of `s` that contains every character of `t`, counting multiplicity (if `t` has two `a`s, the window needs at least two `a`s). If no such window exists, return the empty string `""`. Inputs are guaranteed to have at most one shortest window. The intended solution runs in O(m + n) time.

**Implement:** `def minWindow(self, s: str, t: str) -> str`

## Examples

**Example 1**

```text
Input:  s = "XBYAZCAXB", t = "ABC"
Output: "CAXB"
```

**Example 2**

```text
Input:  s = "aabbc", t = "abb"
Output: "abb"
```

Duplicates in `t` must be matched: the window needs two `b`s.

**Example 3**

```text
Input:  s = "q", t = "qq"
Output: ""
```

`s` has only one `q`, so no window works.

## Constraints

- 1 <= s.length, t.length <= 10^5
- `s` and `t` consist of uppercase and lowercase English letters.
- If a valid window exists, the shortest one is unique.

## Notes

- Characters are case-sensitive.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 76](https://leetcode.com/problems/minimum-window-substring/) for the official statement._
