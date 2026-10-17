# 84. Largest Rectangle in Histogram

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Hard | [Stack](../README.md) | [LeetCode 84](https://leetcode.com/problems/largest-rectangle-in-histogram/) |

## Problem

Given an array `heights` where each value is the height of a histogram bar of width 1, placed side by side, return the area of the largest axis-aligned rectangle that fits entirely inside the histogram. Such a rectangle spans a contiguous range of bars and its height is at most the shortest bar in that range.

**Implement:** `def largestRectangleArea(self, heights: list[int]) -> int`

## Examples

**Example 1**

```text
Input:  heights = [3, 1, 4, 5, 2, 6]
Output: 8
```

Bars at indices 2-5 have minimum height 2, giving `2 * 4 = 8`; bars 2-3 give `4 * 2 = 8` as well.

**Example 2**

```text
Input:  heights = [2, 2, 2]
Output: 6
```

**Example 3**

```text
Input:  heights = [0]
Output: 0
```

## Constraints

- 1 <= heights.length <= 10^5
- 0 <= heights[i] <= 10^4

## Notes

- Aim for O(n) time.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 84](https://leetcode.com/problems/largest-rectangle-in-histogram/) for the official statement._
