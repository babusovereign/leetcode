# 253. Meeting Rooms II

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Intervals](../README.md) | [LeetCode 253](https://leetcode.com/problems/meeting-rooms-ii/) (Premium) |

> LeetCode Premium. The same problem is free to practise on [NeetCode](https://neetcode.io/practice).

## Problem

Given a list of meeting time intervals `intervals[i] = [start, end]`, return the minimum number of conference rooms needed so that every meeting can be held.

A meeting ending at time `t` frees its room in time for another meeting starting at `t`.

**Implement:** `def minMeetingRooms(self, intervals: list[list[int]]) -> int`

## Examples

**Example 1**

```text
Input:  intervals = [[1, 5], [2, 6], [5, 9], [8, 10]]
Output: 2
```

At most two meetings are running at any moment (e.g. `[2, 6]` and `[5, 9]` at time 5).

**Example 2**

```text
Input:  intervals = [[3, 4], [4, 5], [5, 6]]
Output: 1
```

Each meeting starts exactly when the previous ends, so one room suffices.

**Example 3**

```text
Input:  intervals = [[1, 10], [2, 9], [3, 8]]
Output: 3
```

All three are nested, so they all run at once.

## Constraints

- 1 <= intervals.length <= 10^4
- 0 <= start < end <= 10^6

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 253](https://leetcode.com/problems/meeting-rooms-ii/) for the official statement._
