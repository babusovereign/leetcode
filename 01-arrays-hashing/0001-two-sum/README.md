# 1. Two Sum

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Easy | [Arrays & Hashing](../README.md) | [LeetCode 1](https://leetcode.com/problems/two-sum/) |

## Problem

Given an integer array `nums` and an integer `target`, find two different positions `i` and `j` such that `nums[i] + nums[j] == target`, and return their indices. The same element may not be used twice. The indices may be returned in either order.

**Implement:** `def twoSum(self, nums: list[int], target: int) -> list[int]`

## Examples

**Example 1**

```text
Input:  nums = [4, 11, 7, 2], target = 9
Output: [2, 3]
```

`nums[2] + nums[3] = 7 + 2 = 9`.

**Example 2**

```text
Input:  nums = [-3, 8, 5, -1], target = 4
Output: [2, 3]
```

`5 + (-1) = 4`.

**Example 3**

```text
Input:  nums = [6, 6], target = 12
Output: [0, 1]
```

Equal values at different indices are allowed.

## Constraints

- 2 <= nums.length <= 10^4
- -10^9 <= nums[i] <= 10^9
- -10^9 <= target <= 10^9
- Exactly one valid pair exists.

## Notes

- Follow-up: can you do better than O(n^2) time?

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 1](https://leetcode.com/problems/two-sum/) for the official statement._
