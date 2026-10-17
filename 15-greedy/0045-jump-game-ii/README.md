# 45. Jump Game II

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Greedy](../README.md) | [LeetCode 45](https://leetcode.com/problems/jump-game-ii/) |

## Problem

You start at index 0 of an integer array `nums`; `nums[i]` is the longest forward jump you may make from index `i` (any length from 1 to `nums[i]`).

Return the minimum number of jumps needed to reach the last index. The input is guaranteed to allow reaching it.

**Implement:** `def jump(self, nums: list[int]) -> int`

## Examples

**Example 1**

```text
Input:  nums = [3, 1, 4, 1, 1, 1, 2]
Output: 2
```

0 -> 2 (value 4) -> 6 takes two jumps.

**Example 2**

```text
Input:  nums = [1, 1, 1, 1]
Output: 3
```

Each jump can only advance one step.

**Example 3**

```text
Input:  nums = [5]
Output: 0
```

A single-element array needs no jumps.

## Constraints

- 1 <= nums.length <= 10^4
- 0 <= nums[i] <= 1000
- The last index is always reachable.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 45](https://leetcode.com/problems/jump-game-ii/) for the official statement._
