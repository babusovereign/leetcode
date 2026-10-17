# 57. Insert Interval

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Intervals](../README.md) | [LeetCode 57](https://leetcode.com/problems/insert-interval/) |

## Problem

You are given a list of non-overlapping intervals `intervals[i] = [start, end]` sorted by start, and one more interval `newInterval`. Insert `newInterval` so that the list stays sorted by start and still has no overlaps, merging any intervals that overlap it.

Return the resulting list. Intervals that share an endpoint (e.g. `[1, 3]` and `[3, 5]`) count as overlapping.

**Implement:** `def insert(self, intervals: list[list[int]], newInterval: list[int]) -> list[list[int]]`

## Examples

**Example 1**

```text
Input:  intervals = [[1, 3], [5, 7], [9, 12]], newInterval = [6, 10]
Output: [[1, 3], [5, 12]]
```

`[6, 10]` overlaps both `[5, 7]` and `[9, 12]`, so all three merge.

**Example 2**

```text
Input:  intervals = [], newInterval = [2, 4]
Output: [[2, 4]]
```

Empty input: the result is just the new interval.

**Example 3**

```text
Input:  intervals = [[2, 3], [6, 8]], newInterval = [4, 5]
Output: [[2, 3], [4, 5], [6, 8]]
```

No overlap; it slots in between.

## Constraints

- 0 <= intervals.length <= 10^4
- intervals[i].length == 2
- start <= end for every interval
- intervals is sorted by start and has no overlaps.

## Notes

- You may build and return a new list rather than modifying the input in place.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 57](https://leetcode.com/problems/insert-interval/) for the official statement._
