# 53. Maximum Subarray

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Greedy](../README.md) | [LeetCode 53](https://leetcode.com/problems/maximum-subarray/) |

## Problem

Given an integer array `nums`, find the contiguous, non-empty run of elements whose sum is as large as possible, and return that sum.

The subarray must contain at least one element, so an all-negative array still has an answer (its largest single element).

**Implement:** `def maxSubArray(self, nums: list[int]) -> int`

## Examples

**Example 1**

```text
Input:  nums = [2, -5, 3, 4, -1, 2, -8]
Output: 8
```

The run `[3, 4, -1, 2]` sums to 8.

**Example 2**

```text
Input:  nums = [-4, -2, -7]
Output: -2
```

Every element is negative, so the best is the single element `-2`.

**Example 3**

```text
Input:  nums = [6]
Output: 6
```

## Constraints

- 1 <= nums.length <= 10^5
- -10^4 <= nums[i] <= 10^4

## Notes

- Follow-up: can you solve it in O(n) time?

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 53](https://leetcode.com/problems/maximum-subarray/) for the official statement._
