# 338. Counting Bits

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Easy | [Bit Manipulation](../README.md) | [LeetCode 338](https://leetcode.com/problems/counting-bits/) |

## Problem

Given a non-negative integer `n`, return an array `ans` of length `n + 1` where `ans[i]` is the number of `1` bits in the binary representation of `i`, for every `i` from `0` to `n`.

**Implement:** `def countBits(self, n: int) -> list[int]`

## Examples

**Example 1**

```text
Input:  n = 3
Output: [0, 1, 1, 2]
```

0 -> 0, 1 -> 1, 10 -> 1, 11 -> 2.

**Example 2**

```text
Input:  n = 8
Output: [0, 1, 1, 2, 1, 2, 2, 3, 1]
```

**Example 3**

```text
Input:  n = 0
Output: [0]
```

## Constraints

- 0 <= n <= 10^5

## Notes

- Follow-up: compute it in a single O(n) pass without a built-in popcount, reusing earlier answers.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 338](https://leetcode.com/problems/counting-bits/) for the official statement._
