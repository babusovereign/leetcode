# 7. Reverse Integer

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Bit Manipulation](../README.md) | [LeetCode 7](https://leetcode.com/problems/reverse-integer/) |

## Problem

Given a signed 32-bit integer `x`, return the integer formed by reversing its decimal digits, keeping the sign. If the reversed value falls outside the signed 32-bit range `[-2^31, 2^31 - 1]`, return `0`.

Assume your environment cannot store 64-bit integers, so you must detect overflow before it happens.

**Implement:** `def reverse(self, x: int) -> int`

## Examples

**Example 1**

```text
Input:  x = 1250
Output: 521
```

Trailing zeros vanish: `0521` is 521.

**Example 2**

```text
Input:  x = -308
Output: -803
```

**Example 3**

```text
Input:  x = 1563847412
Output: 0
```

Reversed it would be 2147483651, which exceeds 2^31 - 1.

## Constraints

- -2^31 <= x <= 2^31 - 1

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 7](https://leetcode.com/problems/reverse-integer/) for the official statement._
