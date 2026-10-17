# 494. Target Sum

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [2-D Dynamic Programming](../README.md) | [LeetCode 494](https://leetcode.com/problems/target-sum/) |

## Problem

Given an integer array `nums` and an integer `target`, place either a `+` or a `-` in front of every element and evaluate the resulting expression. Return how many of the sign assignments evaluate to exactly `target`.

**Implement:** `def findTargetSumWays(self, nums: list[int], target: int) -> int`

## Examples

**Example 1**

```text
Input:  nums = [2, 1, 1], target = 2
Output: 2
```

+2 +1 -1 and +2 -1 +1.

**Example 2**

```text
Input:  nums = [0, 1], target = 1
Output: 2
```

Edge case: +0 and -0 are different assignments.

**Example 3**

```text
Input:  nums = [4], target = 3
Output: 0
```

## Constraints

- 1 <= nums.length <= 20
- 0 <= nums[i] <= 1000
- 0 <= sum(nums) <= 1000
- -1000 <= target <= 1000

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 494](https://leetcode.com/problems/target-sum/) for the official statement._
