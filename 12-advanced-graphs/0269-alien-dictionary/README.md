# 269. Alien Dictionary

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Hard | [Advanced Graphs](../README.md) | [LeetCode 269](https://leetcode.com/problems/alien-dictionary/) (Premium) |

> LeetCode Premium. The same problem is free to practise on [NeetCode](https://neetcode.io/practice).

## Problem

An alien language uses a subset of lowercase English letters in some unknown order. You are given a list of `words` that is claimed to be sorted lexicographically by that alien order. Derive an ordering of all letters appearing in `words` consistent with the list and return it as a string. If the list cannot be sorted under any ordering (for example, a word comes before its own proper prefix, or the constraints form a cycle), return `""`; if several orderings are valid, return any of them.

**Implement:** `String alienOrder(String[] words)`

## Examples

**Example 1**

```text
Input:  words = ["tea", "ted", "dt", "de", "ee"]
Output: "atde" or "tade" (any valid order)
```

Adjacent pairs give a < d (tea/ted), t < d (ted/dt), t < e (dt/de), and d < e (de/ee). Nothing relates a and t, so either may come first.

**Example 2**

```text
Input:  words = ["xa", "xb", "b"]
Output: "axb" or "xab" (any valid order)
```

We only learn a < b and x < b; x and a can be in either order.

**Example 3**

```text
Input:  words = ["abc", "ab"]
Output: ""
```

A word appears before its own proper prefix, so no ordering is consistent.

## Constraints

- 1 <= words.length <= 100
- 1 <= words[i].length <= 100
- Words contain only lowercase English letters.

## Notes

- Only the first differing letter of each adjacent pair gives information; letters that never get compared can go anywhere.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 269](https://leetcode.com/problems/alien-dictionary/) for the official statement._
