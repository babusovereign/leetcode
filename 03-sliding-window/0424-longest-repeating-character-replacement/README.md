# 424. Longest Repeating Character Replacement

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Sliding Window](../README.md) | [LeetCode 424](https://leetcode.com/problems/longest-repeating-character-replacement/) |

## Problem

Given a string `s` of uppercase English letters and an integer `k`, you may change at most `k` characters of `s` into any other uppercase letter. Return the length of the longest contiguous substring that can be made to consist of a single repeated letter using those changes.

**Implement:** `def characterReplacement(self, s: str, k: int) -> int`

## Examples

**Example 1**

```text
Input:  s = "AABCABB", k = 2
Output: 5
```

Change the `C` and the second `A` in `"BCABB"` to get `"BBBBB"`.

**Example 2**

```text
Input:  s = "ABCD", k = 0
Output: 1
```

**Example 3**

```text
Input:  s = "XYXY", k = 4
Output: 4
```

`k` is large enough to make the whole string uniform.

## Constraints

- 1 <= s.length <= 10^5
- `s` contains only uppercase English letters.
- 0 <= k <= s.length

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 424](https://leetcode.com/problems/longest-repeating-character-replacement/) for the official statement._
