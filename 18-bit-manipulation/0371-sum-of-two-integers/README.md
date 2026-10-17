# 371. Sum of Two Integers

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Bit Manipulation](../README.md) | [LeetCode 371](https://leetcode.com/problems/sum-of-two-integers/) |

## Problem

Given two integers `a` and `b`, return their sum without using the `+` or `-` operators.

The intended approach uses bitwise operations: XOR for the sum without carries, AND plus a left shift for the carries, repeated until no carry remains.

**Implement:** `def getSum(self, a: int, b: int) -> int`

## Examples

**Example 1**

```text
Input:  a = 5, b = 9
Output: 14
```

**Example 2**

```text
Input:  a = -7, b = 3
Output: -4
```

**Example 3**

```text
Input:  a = 0, b = -1
Output: -1
```

## Constraints

- -1000 <= a, b <= 1000

## Notes

- In Python, integers are unbounded, so you must mask to 32 bits (e.g. `& 0xFFFFFFFF`) and convert back to a signed value at the end.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 371](https://leetcode.com/problems/sum-of-two-integers/) for the official statement._
