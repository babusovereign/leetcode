# 252. Meeting Rooms

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Easy | [Intervals](../README.md) | [LeetCode 252](https://leetcode.com/problems/meeting-rooms/) (Premium) |

> LeetCode Premium. The same problem is free to practise on [NeetCode](https://neetcode.io/practice).

## Problem

You are given a list of meeting time intervals `intervals[i] = [start, end]`. Determine whether a single person could attend all of them, i.e. no two meetings overlap.

A meeting that ends at time `t` does not conflict with one that starts at time `t`. Return `true` if all meetings can be attended, otherwise `false`.

**Implement:** `def canAttendMeetings(self, intervals: list[list[int]]) -> bool`

## Examples

**Example 1**

```text
Input:  intervals = [[9, 10], [1, 3], [4, 9]]
Output: true
```

Sorted they run back to back: 1-3, 4-9, 9-10.

**Example 2**

```text
Input:  intervals = [[2, 6], [5, 8]]
Output: false
```

Times 5 to 6 are double-booked.

**Example 3**

```text
Input:  intervals = []
Output: true
```

No meetings, no conflicts.

## Constraints

- 0 <= intervals.length <= 10^4
- intervals[i].length == 2
- start < end for every meeting

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 252](https://leetcode.com/problems/meeting-rooms/) for the official statement._
