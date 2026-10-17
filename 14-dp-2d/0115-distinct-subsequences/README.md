# 115. Distinct Subsequences

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Hard | [2-D Dynamic Programming](../README.md) | [LeetCode 115](https://leetcode.com/problems/distinct-subsequences/) |

## Problem

Given strings `s` and `t`, count how many distinct ways `t` appears as a subsequence of `s`. Two ways differ if they use a different set of character positions in `s`. The answer fits in a 32-bit integer.

**Implement:** `def numDistinct(self, s: str, t: str) -> int`

## Examples

**Example 1**

```text
Input:  s = "aabb", t = "ab"
Output: 4
```

Either "a" paired with either "b": 2 x 2.

**Example 2**

```text
Input:  s = "banana", t = "ban"
Output: 3
```

"b", then one of the first two "a"s and a later "n".

**Example 3**

```text
Input:  s = "abc", t = "d"
Output: 0
```

Edge case: no match at all.

## Constraints

- 1 <= s.length, t.length <= 1000
- `s` and `t` are English letters.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 115](https://leetcode.com/problems/distinct-subsequences/) for the official statement._
