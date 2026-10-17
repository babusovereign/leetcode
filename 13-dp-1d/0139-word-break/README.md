# 139. Word Break

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [1-D Dynamic Programming](../README.md) | [LeetCode 139](https://leetcode.com/problems/word-break/) |

## Problem

Given a string `s` and a list of words `wordDict`, decide whether `s` can be split into a sequence of one or more dictionary words with nothing left over. Words may be reused any number of times. Return `true` or `false`.

**Implement:** `def wordBreak(self, s: str, wordDict: list[str]) -> bool`

## Examples

**Example 1**

```text
Input:  s = "catsdog", wordDict = ["cats", "dog", "cat"]
Output: true
```

"cats" + "dog".

**Example 2**

```text
Input:  s = "aaab", wordDict = ["a", "aa"]
Output: false
```

No word covers the trailing "b".

**Example 3**

```text
Input:  s = "gogogo", wordDict = ["go"]
Output: true
```

The same word can be reused.

## Constraints

- 1 <= s.length <= 300
- 1 <= wordDict.length <= 1000
- 1 <= wordDict[i].length <= 20
- `s` and all words are lowercase English letters.
- All words in `wordDict` are distinct.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 139](https://leetcode.com/problems/word-break/) for the official statement._
