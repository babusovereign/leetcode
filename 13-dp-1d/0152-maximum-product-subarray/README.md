# 152. Maximum Product Subarray

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [1-D Dynamic Programming](../README.md) | [LeetCode 152](https://leetcode.com/problems/maximum-product-subarray/) |

## Problem

Given an integer array `nums`, find the non-empty contiguous subarray whose elements have the largest product, and return that product. The answer is guaranteed to fit in a 32-bit integer.

**Implement:** `def maxProduct(self, nums: list[int]) -> int`

## Examples

**Example 1**

```text
Input:  nums = [3, -1, 4]
Output: 4
```

The single element [4]; any subarray spanning -1 is negative.

**Example 2**

```text
Input:  nums = [-2, 3, -4]
Output: 24
```

Two negatives cancel: -2 * 3 * -4.

**Example 3**

```text
Input:  nums = [-3, 0, -1]
Output: 0
```

Edge case: zero beats every negative option.

## Constraints

- 1 <= nums.length <= 2 * 10^4
- -10 <= nums[i] <= 10
- The product of any subarray fits in a 32-bit integer.

## Notes

- Track both the running maximum and minimum, since a negative number flips them.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 152](https://leetcode.com/problems/maximum-product-subarray/) for the official statement._
