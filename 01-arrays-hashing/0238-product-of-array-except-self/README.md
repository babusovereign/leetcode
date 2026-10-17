# 238. Product of Array Except Self

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Arrays & Hashing](../README.md) | [LeetCode 238](https://leetcode.com/problems/product-of-array-except-self/) |

## Problem

Given an integer array `nums`, return an array `answer` where `answer[i]` is the product of every element of `nums` except `nums[i]`. Solve it in O(n) time without using division. Every prefix and suffix product is guaranteed to fit in a 32-bit integer.

**Implement:** `def productExceptSelf(self, nums: list[int]) -> list[int]`

## Examples

**Example 1**

```text
Input:  nums = [2, 5, 3, 4]
Output: [60, 24, 40, 30]
```

For example, `answer[1] = 2 * 3 * 4 = 24`.

**Example 2**

```text
Input:  nums = [3, 0, -2, 5]
Output: [0, -30, 0, 0]
```

Only the position holding the zero gets a non-zero product.

**Example 3**

```text
Input:  nums = [0, 4, 0]
Output: [0, 0, 0]
```

With two zeros, every product includes a zero.

## Constraints

- 2 <= nums.length <= 10^5
- -30 <= nums[i] <= 30
- No division operator.
- Prefix/suffix products fit in a 32-bit integer.

## Notes

- Follow-up: can you use O(1) extra space, not counting the output array?

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 238](https://leetcode.com/problems/product-of-array-except-self/) for the official statement._
