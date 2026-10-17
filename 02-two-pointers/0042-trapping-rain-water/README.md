# 42. Trapping Rain Water

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Hard | [Two Pointers](../README.md) | [LeetCode 42](https://leetcode.com/problems/trapping-rain-water/) |

## Problem

You are given an array `height` of non-negative integers describing an elevation profile, where each element is the height of a bar of width 1. After rain, water collects in the dips between taller bars. Return the total units of water trapped: the water above position `i` is `min(tallest bar to its left, tallest bar to its right) - height[i]`, counting only positive amounts (each side's maximum includes `i` itself).

**Implement:** `def trap(self, height: list[int]) -> int`

## Examples

**Example 1**

```text
Input:  height = [3, 0, 1, 0, 4, 1, 2]
Output: 9
```

Positions 1-3 hold 3 + 2 + 3 units; position 5 holds 1 unit.

**Example 2**

```text
Input:  height = [1, 2, 3, 4]
Output: 0
```

A steadily rising profile has no basin.

**Example 3**

```text
Input:  height = [5, 1, 5]
Output: 4
```

## Constraints

- 1 <= height.length <= 2 * 10^4
- 0 <= height[i] <= 10^5

## Notes

- Follow-up: solve it in O(n) time and O(1) extra space.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 42](https://leetcode.com/problems/trapping-rain-water/) for the official statement._
