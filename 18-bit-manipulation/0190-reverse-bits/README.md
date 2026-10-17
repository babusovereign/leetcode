# 190. Reverse Bits

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Easy | [Bit Manipulation](../README.md) | [LeetCode 190](https://leetcode.com/problems/reverse-bits/) |

## Problem

Given a 32-bit unsigned integer `n`, reverse the order of its 32 bits (bit 0 becomes bit 31, bit 1 becomes bit 30, and so on) and return the result as an unsigned integer.

**Implement:** `def reverseBits(self, n: int) -> int`

## Examples

**Example 1**

```text
Input:  n = 1
Output: 2147483648
```

`0...01` becomes `10...0`, which is 2^31.

**Example 2**

```text
Input:  n = 6
Output: 1610612736
```

`110` at the low end moves to the top: `0110...0`.

**Example 3**

```text
Input:  n = 4294967294
Output: 2147483647
```

Thirty-one 1s followed by a 0 reverses to a 0 followed by thirty-one 1s.

## Constraints

- The input is a 32-bit unsigned integer (0 <= n <= 2^32 - 1).

## Notes

- In Java there is no unsigned int, so inputs at or above 2^31 arrive as negative numbers; the bit pattern is what matters.
- Follow-up: if called many times, how would you optimize (e.g. a byte lookup table)?

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 190](https://leetcode.com/problems/reverse-bits/) for the official statement._
