# 15. 3Sum

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Two Pointers](../README.md) | [LeetCode 15](https://leetcode.com/problems/3sum/) |

## Problem

Given an integer array `nums`, return every distinct triplet of values `[a, b, c]` taken from three different positions such that `a + b + c == 0`. The result must not contain the same triplet (as a multiset of values) twice. Triplets and the values inside them may be returned in any order.

**Implement:** `def threeSum(self, nums: list[int]) -> list[list[int]]`

## Examples

**Example 1**

```text
Input:  nums = [-3, 1, 2, -1, 0, 1, 2]
Output: [[-3, 1, 2], [-1, 0, 1]] (any order)
```

`[-3, 1, 2]` can be formed in more than one way but is listed once.

**Example 2**

```text
Input:  nums = [4, -2, 5]
Output: []
```

**Example 3**

```text
Input:  nums = [0, 0, 0, 0]
Output: [[0, 0, 0]]
```

## Constraints

- 3 <= nums.length <= 3000
- -10^5 <= nums[i] <= 10^5

## Notes

- Clarify that uniqueness is by values, not by index positions.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 15](https://leetcode.com/problems/3sum/) for the official statement._
