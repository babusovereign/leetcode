# 268. Missing Number

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Easy | [Bit Manipulation](../README.md) | [LeetCode 268](https://leetcode.com/problems/missing-number/) |

## Problem

You are given an array `nums` of `n` distinct integers, each taken from the range `0` to `n` inclusive. Exactly one number in that range is absent; return it.

**Implement:** `def missingNumber(self, nums: list[int]) -> int`

## Examples

**Example 1**

```text
Input:  nums = [3, 0, 1]
Output: 2
```

n = 3, so the range is 0..3 and 2 is missing.

**Example 2**

```text
Input:  nums = [0, 1]
Output: 2
```

The missing value can be `n` itself.

**Example 3**

```text
Input:  nums = [4, 2, 5, 0, 1]
Output: 3
```

## Constraints

- n == nums.length
- 1 <= n <= 10^4
- 0 <= nums[i] <= n
- All values are distinct.

## Notes

- Follow-up: O(n) time and O(1) extra space (XOR or the arithmetic-sum trick).

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 268](https://leetcode.com/problems/missing-number/) for the official statement._
