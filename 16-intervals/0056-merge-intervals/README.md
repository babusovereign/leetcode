# 56. Merge Intervals

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Intervals](../README.md) | [LeetCode 56](https://leetcode.com/problems/merge-intervals/) |

## Problem

Given an array of intervals `intervals[i] = [start, end]` in no particular order, merge every group of overlapping intervals into a single interval and return the resulting non-overlapping intervals.

Intervals that touch at an endpoint (e.g. `[1, 2]` and `[2, 3]`) are considered overlapping.

**Implement:** `def merge(self, intervals: list[list[int]]) -> list[list[int]]`

## Examples

**Example 1**

```text
Input:  intervals = [[8, 10], [1, 4], [3, 5], [12, 12]]
Output: [[1, 5], [8, 10], [12, 12]]
```

`[1, 4]` and `[3, 5]` merge; the rest stand alone. Any output order is accepted.

**Example 2**

```text
Input:  intervals = [[2, 6], [6, 9]]
Output: [[2, 9]]
```

Touching endpoints merge.

**Example 3**

```text
Input:  intervals = [[1, 10], [2, 3], [4, 5]]
Output: [[1, 10]]
```

One interval contains the other two.

## Constraints

- 1 <= intervals.length <= 10^4
- intervals[i].length == 2
- 0 <= start <= end <= 10^4

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 56](https://leetcode.com/problems/merge-intervals/) for the official statement._
