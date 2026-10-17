# 1851. Minimum Interval to Include Each Query

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Hard | [Intervals](../README.md) | [LeetCode 1851](https://leetcode.com/problems/minimum-interval-to-include-each-query/) |

## Problem

You are given a list of closed intervals `intervals[i] = [left, right]` and an array of integers `queries`. The size of an interval is `right - left + 1` (the count of integers it covers).

For each query `q`, find the smallest-size interval that contains `q` (i.e. `left <= q <= right`) and report its size, or `-1` if no interval contains `q`. Return the answers in the same order as `queries`.

**Implement:** `def minInterval(self, intervals: list[list[int]], queries: list[int]) -> list[int]`

## Examples

**Example 1**

```text
Input:  intervals = [[1, 4], [2, 3], [5, 9], [6, 6]], queries = [3, 6, 4, 10]
Output: [2, 1, 4, -1]
```

Query 3 fits `[2, 3]` (size 2); 6 fits `[6, 6]` (size 1); 4 only fits `[1, 4]` (size 4); nothing covers 10.

**Example 2**

```text
Input:  intervals = [[2, 2], [10, 20]], queries = [1, 2, 15]
Output: [-1, 1, 11]
```

## Constraints

- 1 <= intervals.length <= 10^5
- 1 <= queries.length <= 10^5
- 1 <= left <= right <= 10^7
- 1 <= queries[j] <= 10^7

<details>
<summary>Hint (spoiler)</summary>

- Brute force is O(n * q); the intended approach sorts both lists and uses a min-heap.

</details>

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 1851](https://leetcode.com/problems/minimum-interval-to-include-each-query/) for the official statement._
