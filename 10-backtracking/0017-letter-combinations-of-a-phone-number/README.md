# 17. Letter Combinations of a Phone Number

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Backtracking](../README.md) | [LeetCode 17](https://leetcode.com/problems/letter-combinations-of-a-phone-number/) |

## Problem

Given a string of digits from `2` to `9`, return every letter string it could represent using a classic phone keypad mapping: `2`=abc, `3`=def, `4`=ghi, `5`=jkl, `6`=mno, `7`=pqrs, `8`=tuv, `9`=wxyz. Each digit contributes exactly one of its letters, in the same position. Return the strings in any order; for an empty input return an empty list.

**Implement:** `List<String> letterCombinations(String digits)`

## Examples

**Example 1**

```text
Input:  digits = "79"
Output: ["pw", "px", "py", "pz", "qw", "qx", "qy", "qz", "rw", "rx", "ry", "rz", "sw", "sx", "sy", "sz"] (any order)
```

7 maps to 4 letters and 9 maps to 4 letters, giving 16 strings.

**Example 2**

```text
Input:  digits = "5"
Output: ["j", "k", "l"] (any order)
```

**Example 3**

```text
Input:  digits = ""
Output: []
```

An empty input produces an empty list, not a list containing the empty string.

## Constraints

- 0 <= digits.length <= 4
- Each character is a digit from `2` to `9`.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 17](https://leetcode.com/problems/letter-combinations-of-a-phone-number/) for the official statement._
