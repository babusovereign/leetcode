# 134. Gas Station

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Greedy](../README.md) | [LeetCode 134](https://leetcode.com/problems/gas-station/) |

## Problem

There are `n` gas stations arranged in a circle. Station `i` lets you fill up `gas[i]` units, and driving from station `i` to station `i + 1` (wrapping from the last back to the first) burns `cost[i]` units. Your car has an unlimited tank but starts empty.

Return the index of a station from which you can drive all the way around the circle once, clockwise, without the tank ever going negative. Return `-1` if no such station exists. When a solution exists it is guaranteed to be unique.

**Implement:** `def canCompleteCircuit(self, gas: list[int], cost: list[int]) -> int`

## Examples

**Example 1**

```text
Input:  gas = [2, 5, 1, 4], cost = [3, 2, 4, 2]
Output: 1
```

Starting at index 1 the tank reads 3, 0, 2, 1 after each leg, never dipping below zero.

**Example 2**

```text
Input:  gas = [1, 2, 3], cost = [2, 3, 2]
Output: -1
```

Total gas (6) is less than total cost (7), so no start works.

**Example 3**

```text
Input:  gas = [4], cost = [4]
Output: 0
```

One station: fill 4, spend 4 to return to itself.

## Constraints

- n == gas.length == cost.length
- 1 <= n <= 10^5
- 0 <= gas[i], cost[i] <= 10^4
- If an answer exists, it is unique.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 134](https://leetcode.com/problems/gas-station/) for the official statement._
