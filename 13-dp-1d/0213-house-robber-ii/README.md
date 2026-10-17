# 213. House Robber II

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [1-D Dynamic Programming](../README.md) | [LeetCode 213](https://leetcode.com/problems/house-robber-ii/) |

## Problem

Same as House Robber, except the houses are arranged in a circle: the first and last houses in `nums` are also neighbors, so you cannot take from both. Every other adjacency rule is unchanged. Return the maximum total you can collect.

**Implement:** `def rob(self, nums: list[int]) -> int`

## Examples

**Example 1**

```text
Input:  nums = [4, 2, 6]
Output: 6
```

Houses 0 and 2 are adjacent on the circle, so the best is just the 6.

**Example 2**

```text
Input:  nums = [2, 9, 3, 1]
Output: 10
```

Take houses 1 and 3: 9 + 1.

**Example 3**

```text
Input:  nums = [6]
Output: 6
```

Edge case: a single house is not its own neighbor.

## Constraints

- 1 <= nums.length <= 100
- 0 <= nums[i] <= 1000

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 213](https://leetcode.com/problems/house-robber-ii/) for the official statement._
