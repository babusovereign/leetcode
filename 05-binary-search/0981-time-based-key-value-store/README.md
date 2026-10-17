# 981. Time Based Key-Value Store

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Binary Search](../README.md) | [LeetCode 981](https://leetcode.com/problems/time-based-key-value-store/) |

## Problem

Design a key-value store that keeps every value a key has had, each tagged with the timestamp at which it was written, and can answer queries about the past. Implement a `TimeMap` class with: a constructor; `set(key, value, timestamp)` to record `value` for `key` at time `timestamp`; and `get(key, timestamp)` to return the value from the latest `set` for `key` whose timestamp is `<= timestamp`, or `""` if there is none.

Timestamps passed to `set` are strictly increasing across all calls, so each key's history arrives already sorted.

**Implement:** `class TimeMap: set(key: str, value: str, timestamp: int) -> None, get(key: str, timestamp: int) -> str`

## Examples

**Example 1**

```text
Input:  ops = ["TimeMap", "set", "set", "get", "get", "get", "get", "get"]
args = [[], ["color", "red", 3], ["color", "blue", 8], ["color", 2], ["color", 3], ["color", 5], ["color", 10], ["size", 9]]
Output: [null, null, null, "", "red", "red", "blue", ""]
```

At time 2 nothing has been written yet; at 5 the latest write is `"red"` (time 3); at 10 it is `"blue"` (time 8). `"size"` was never set.

## Constraints

- 1 <= key.length, value.length <= 100
- 1 <= timestamp <= 10^7
- Timestamps across `set` calls are strictly increasing.
- At most 2 * 10^5 calls to `set` and `get` in total.

## Notes

- The example input lists each method call and its arguments; the output lists each call's return value (`null` for the constructor and `set`).

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 981](https://leetcode.com/problems/time-based-key-value-store/) for the official statement._
