# 312. Burst Balloons

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Hard | [2-D Dynamic Programming](../README.md) | [LeetCode 312](https://leetcode.com/problems/burst-balloons/) |

## Problem

You have a row of balloons with values `nums`. Bursting balloon `i` earns `left * nums[i] * right` coins, where `left` and `right` are the values of its current nearest unburst neighbors (treated as `1` when there is no neighbor on that side). After a burst, its neighbors become adjacent. Burst all the balloons in whatever order maximizes the total, and return that total.

**Implement:** `def maxCoins(self, nums: list[int]) -> int`

## Examples

**Example 1**

```text
Input:  nums = [2, 4, 3]
Output: 33
```

Burst 4 (2*4*3 = 24), then 2 (1*2*3 = 6), then 3 (1*3*1 = 3).

**Example 2**

```text
Input:  nums = [1, 5, 2]
Output: 20
```

Burst 2 (5*2*1 = 10), then 1 (1*1*5 = 5), then 5 (1*5*1 = 5).

**Example 3**

```text
Input:  nums = [6]
Output: 6
```

Edge case: one balloon, 1 * 6 * 1.

## Constraints

- 1 <= nums.length <= 300
- 0 <= nums[i] <= 100

## Notes

- Think about which balloon is burst last within an interval, not first.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 312](https://leetcode.com/problems/burst-balloons/) for the official statement._
