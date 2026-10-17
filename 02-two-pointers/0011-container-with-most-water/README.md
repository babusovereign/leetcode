# 11. Container With Most Water

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Two Pointers](../README.md) | [LeetCode 11](https://leetcode.com/problems/container-with-most-water/) |

## Problem

You are given an array `height` where `height[i]` is the height of a vertical wall standing at x-coordinate `i`. Choose two walls; together with the x-axis they form a container whose water level is limited by the shorter wall. Return the maximum amount of water such a container can hold, i.e. the maximum over pairs `i < j` of `(j - i) * min(height[i], height[j])`. The container cannot be tilted.

**Implement:** `def maxArea(self, height: list[int]) -> int`

## Examples

**Example 1**

```text
Input:  height = [2, 7, 3, 6, 1, 5]
Output: 20
```

Walls at indices 1 and 5: width 4, limited by height 5.

**Example 2**

```text
Input:  height = [4, 4]
Output: 4
```

**Example 3**

```text
Input:  height = [0, 9, 0]
Output: 0
```

Every pair includes a zero-height wall.

## Constraints

- 2 <= height.length <= 10^5
- 0 <= height[i] <= 10^4

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 11](https://leetcode.com/problems/container-with-most-water/) for the official statement._
