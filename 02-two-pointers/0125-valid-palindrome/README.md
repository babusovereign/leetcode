# 125. Valid Palindrome

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Easy | [Two Pointers](../README.md) | [LeetCode 125](https://leetcode.com/problems/valid-palindrome/) |

## Problem

Given a string `s`, decide whether it reads the same forwards and backwards after converting all uppercase letters to lowercase and discarding every character that is not a letter or digit. Return `true` if it does, `false` otherwise.

**Implement:** `def isPalindrome(self, s: str) -> bool`

## Examples

**Example 1**

```text
Input:  s = "Step on no pets!"
Output: true
```

After cleaning it becomes `"steponnopets"`, which is a palindrome.

**Example 2**

```text
Input:  s = "ab2a"
Output: false
```

Digits are kept: `"ab2a"` reversed is `"a2ba"`.

**Example 3**

```text
Input:  s = ".,  "
Output: true
```

Nothing remains after cleaning; an empty string counts as a palindrome.

## Constraints

- 1 <= s.length <= 2 * 10^5
- `s` consists of printable ASCII characters.

## Notes

- Can you do it with O(1) extra space, without building the cleaned string?

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 125](https://leetcode.com/problems/valid-palindrome/) for the official statement._
