# 50. Pow(x, n)

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Math & Geometry](../README.md) | [LeetCode 50](https://leetcode.com/problems/powx-n/) |

## Problem

Implement `pow(x, n)`: return the floating-point number `x` raised to the integer power `n`. The exponent may be zero or negative (a negative exponent means `1 / x^|n|`).

The naive loop of `|n|` multiplications is too slow for large exponents; aim for O(log |n|) multiplications.

**Implement:** `def myPow(self, x: float, n: int) -> float`

## Examples

**Example 1**

```text
Input:  x = 3.0, n = 4
Output: 81.00000
```

**Example 2**

```text
Input:  x = 2.0, n = -3
Output: 0.12500
```

2^-3 = 1 / 8.

**Example 3**

```text
Input:  x = 1.5, n = 0
Output: 1.00000
```

Anything to the power 0 is 1.

## Constraints

- -100.0 < x < 100.0
- -2^31 <= n <= 2^31 - 1
- If x is 0, n is positive.
- -10^4 <= x^n <= 10^4

## Notes

- Watch out for `n = -2^31`: negating it overflows a 32-bit int in Java/C++.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 50](https://leetcode.com/problems/powx-n/) for the official statement._
