# 49. Group Anagrams

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Arrays & Hashing](../README.md) | [LeetCode 49](https://leetcode.com/problems/group-anagrams/) |

## Problem

Given an array of strings `strs`, partition it into groups where every string in a group is an anagram of every other string in that group (same letters with the same counts). Return the list of groups; neither the groups nor the strings within a group need to be in any particular order.

**Implement:** `def groupAnagrams(self, strs: list[str]) -> list[list[str]]`

## Examples

**Example 1**

```text
Input:  strs = ["tea", "cat", "eat", "act", "bat"]
Output: [["tea", "eat"], ["cat", "act"], ["bat"]] (any order)
```

**Example 2**

```text
Input:  strs = [""]
Output: [[""]]
```

The empty string forms its own group.

**Example 3**

```text
Input:  strs = ["ab", "ba", "ab"]
Output: [["ab", "ba", "ab"]]
```

Duplicate strings stay in the output and belong to the same group.

## Constraints

- 1 <= strs.length <= 10^4
- 0 <= strs[i].length <= 100
- Strings contain only lowercase English letters.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 49](https://leetcode.com/problems/group-anagrams/) for the official statement._
