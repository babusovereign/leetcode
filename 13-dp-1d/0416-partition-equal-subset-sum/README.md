# 416. Partition Equal Subset Sum

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [1-D Dynamic Programming](../README.md) | [LeetCode 416](https://leetcode.com/problems/partition-equal-subset-sum/) |

## Problem

Given an array `nums` of positive integers, decide whether it can be split into two groups (every element in exactly one group) whose sums are equal. Return `true` or `false`.

**Implement:** `def canPartition(self, nums: list[int]) -> bool`

## Examples

**Example 1**

```text
Input:  nums = [3, 1, 5, 9, 2]
Output: true
```

{9, 1} and {3, 5, 2} both sum to 10.

**Example 2**

```text
Input:  nums = [2, 3, 7]
Output: false
```

The total is 12, but no subset sums to 6.

**Example 3**

```text
Input:  nums = [3, 1, 5, 9, 4]
Output: false
```

Even total (22), but no subset reaches 11.

## Constraints

- 1 <= nums.length <= 200
- 1 <= nums[i] <= 100

## Notes

- An odd total can be rejected immediately.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 416](https://leetcode.com/problems/partition-equal-subset-sum/) for the official statement._
