# 55. Jump Game

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Greedy](../README.md) | [LeetCode 55](https://leetcode.com/problems/jump-game/) |

## Problem

You start at index 0 of an array `nums` of non-negative integers. The value at each index is the maximum number of positions you may jump forward from there (any jump length from 1 up to that value is allowed).

Return `true` if you can land on the last index, otherwise `false`.

**Implement:** `def canJump(self, nums: list[int]) -> bool`

## Examples

**Example 1**

```text
Input:  nums = [1, 3, 0, 0, 2, 1]
Output: true
```

Jump 0 -> 1, then from index 1 jump 3 to index 4, then 1 more to index 5.

**Example 2**

```text
Input:  nums = [3, 1, 1, 0, 5]
Output: false
```

Every path gets stuck on the `0` at index 3.

**Example 3**

```text
Input:  nums = [0]
Output: true
```

You already stand on the last index.

## Constraints

- 1 <= nums.length <= 10^4
- 0 <= nums[i] <= 10^5

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 55](https://leetcode.com/problems/jump-game/) for the official statement._
