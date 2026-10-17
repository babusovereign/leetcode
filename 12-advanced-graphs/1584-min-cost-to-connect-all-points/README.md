# 1584. Min Cost to Connect All Points

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Advanced Graphs](../README.md) | [LeetCode 1584](https://leetcode.com/problems/min-cost-to-connect-all-points/) |

## Problem

You are given an array of distinct points `points[i] = [x, y]` on a 2D integer grid. Connecting two points costs their Manhattan distance, `|x1 - x2| + |y1 - y2|`. Return the minimum total cost to connect all points so that there is exactly one simple path between any two of them (i.e. the weight of a minimum spanning tree over the complete graph).

**Implement:** `int minCostConnectPoints(int[][] points)`

## Examples

**Example 1**

```text
Input:  points = [[0, 0], [2, 2], [3, 10], [5, 2], [7, 0]]
Output: 20
```

**Example 2**

```text
Input:  points = [[1, 1], [4, 5]]
Output: 7
```

|1 - 4| + |1 - 5| = 7.

**Example 3**

```text
Input:  points = [[-3, 7]]
Output: 0
```

A single point needs no connections.

## Constraints

- 1 <= points.length <= 1000
- -10^6 <= x, y <= 10^6
- All points are distinct.

## Notes

- The graph is complete (about n^2/2 edges), so O(n^2) Prim's is a natural fit.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 1584](https://leetcode.com/problems/min-cost-to-connect-all-points/) for the official statement._
