# 91. Decode Ways

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [1-D Dynamic Programming](../README.md) | [LeetCode 91](https://leetcode.com/problems/decode-ways/) |

## Problem

Letters are encoded as numbers: `A` -> `"1"`, `B` -> `"2"`, ..., `Z` -> `"26"`. Given a string `s` of digits, return how many different ways it can be split into pieces that each map back to a letter. A piece with a leading zero (such as `"06"`) is not valid, and neither is `"0"` on its own. If no valid split exists, return `0`.

**Implement:** `def numDecodings(self, s: str) -> int`

## Examples

**Example 1**

```text
Input:  s = "2611"
Output: 4
```

2|6|1|1, 26|1|1, 2|6|11, 26|11.

**Example 2**

```text
Input:  s = "10"
Output: 1
```

Only "10" (J) works; "1"|"0" is invalid.

**Example 3**

```text
Input:  s = "301"
Output: 0
```

Edge case: "30" is out of range and "0" alone is invalid, so nothing decodes.

## Constraints

- 1 <= s.length <= 100
- `s` contains only digits and may contain leading zeros.
- The answer fits in a 32-bit integer.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 91](https://leetcode.com/problems/decode-ways/) for the official statement._
