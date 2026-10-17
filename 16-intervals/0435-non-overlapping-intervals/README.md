# 435. Non-overlapping Intervals

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Intervals](../README.md) | [LeetCode 435](https://leetcode.com/problems/non-overlapping-intervals/) |

## Problem

Given an array of intervals `intervals[i] = [start, end]`, return the minimum number of intervals you must delete so that the remaining intervals do not overlap one another.

Intervals that only touch at an endpoint, such as `[1, 2]` and `[2, 3]`, are not considered overlapping here.

**Implement:** `def eraseOverlapIntervals(self, intervals: list[list[int]]) -> int`

## Examples

**Example 1**

```text
Input:  intervals = [[1, 4], [2, 3], [3, 6], [5, 7]]
Output: 2
```

Remove `[1, 4]` and `[3, 6]`, keeping `[2, 3]` and `[5, 7]`.

**Example 2**

```text
Input:  intervals = [[1, 2], [2, 3], [3, 4]]
Output: 0
```

They only touch, so nothing needs removing.

**Example 3**

```text
Input:  intervals = [[0, 5], [0, 5], [0, 5]]
Output: 2
```

Identical intervals: keep one.

## Constraints

- 1 <= intervals.length <= 10^5
- intervals[i].length == 2
- -5 * 10^4 <= start < end <= 5 * 10^4

## Notes

- Note the endpoint rule differs from Merge Intervals: here touching is allowed.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 435](https://leetcode.com/problems/non-overlapping-intervals/) for the official statement._
