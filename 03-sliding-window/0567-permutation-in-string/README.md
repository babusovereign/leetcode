# 567. Permutation in String

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Sliding Window](../README.md) | [LeetCode 567](https://leetcode.com/problems/permutation-in-string/) |

## Problem

Given two strings `s1` and `s2`, return `true` if some contiguous substring of `s2` is a rearrangement (permutation) of `s1`, i.e. it has exactly the same characters with the same counts and the same length as `s1`. Otherwise return `false`.

**Implement:** `def checkInclusion(self, s1: str, s2: str) -> bool`

## Examples

**Example 1**

```text
Input:  s1 = "cab", s2 = "xxbacyz"
Output: true
```

`"bac"` (indices 2-4) is a permutation of `"cab"`.

**Example 2**

```text
Input:  s1 = "aab", s2 = "abcab"
Output: false
```

No window of length 3 contains two `a`s and one `b`.

**Example 3**

```text
Input:  s1 = "hello", s2 = "hi"
Output: false
```

`s2` is shorter than `s1`.

## Constraints

- 1 <= s1.length, s2.length <= 10^4
- Both strings contain only lowercase English letters.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 567](https://leetcode.com/problems/permutation-in-string/) for the official statement._
