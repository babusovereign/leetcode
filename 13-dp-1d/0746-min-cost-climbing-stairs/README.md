# 746. Min Cost Climbing Stairs

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Easy | [1-D Dynamic Programming](../README.md) | [LeetCode 746](https://leetcode.com/problems/min-cost-climbing-stairs/) |

## Problem

You are given an array `cost` where `cost[i]` is the price you pay when you step on stair `i`. After paying for a stair you may climb 1 or 2 stairs from it. You may start on either stair `0` or stair `1` for free (you pay that stair's cost only when you leave it), and the goal is to reach the position just past the last stair. Return the minimum total cost to get there.

**Implement:** `def minCostClimbingStairs(self, cost: list[int]) -> int`

## Examples

**Example 1**

```text
Input:  cost = [5, 1, 8, 1]
Output: 2
```

Start at index 1 (pay 1), jump to index 3 (pay 1), then step off the top.

**Example 2**

```text
Input:  cost = [3, 7]
Output: 3
```

Edge case: start at index 0, pay 3, and jump 2 to the top.

**Example 3**

```text
Input:  cost = [2, 2, 9, 2, 2, 9, 2]
Output: 8
```

## Constraints

- 2 <= cost.length <= 1000
- 0 <= cost[i] <= 999

## Notes

- The "top" is index `cost.length`, one past the last stair.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 746](https://leetcode.com/problems/min-cost-climbing-stairs/) for the official statement._
