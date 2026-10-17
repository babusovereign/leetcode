# 973. K Closest Points to Origin

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Heap / Priority Queue](../README.md) | [LeetCode 973](https://leetcode.com/problems/k-closest-points-to-origin/) |

## Problem

Given a list of points on the X-Y plane, `points[i] = [x, y]`, and an integer `k`, return the `k` points nearest to the origin `(0, 0)` using ordinary Euclidean distance. The result may be in any order, and the answer is guaranteed to be unique (no tie at the k-th boundary).

**Implement:** `int[][] kClosest(int[][] points, int k)`

## Examples

**Example 1**

```text
Input:  points = [[3, 4], [-1, 1], [2, -2], [0, 5]], k = 2
Output: [[-1, 1], [2, -2]] (any order)
```

Squared distances are 25, 2, 8, 25, so the two closest are [-1, 1] and [2, -2].

**Example 2**

```text
Input:  points = [[-2, -3], [1, 0]], k = 2
Output: [[1, 0], [-2, -3]] (any order)
```

When k equals the number of points, return all of them.

## Constraints

- 1 <= k <= points.length <= 10^4
- -10^4 <= x, y <= 10^4
- The set of k closest points is unique.

## Notes

- Compare squared distances to avoid square roots and floating point.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 973](https://leetcode.com/problems/k-closest-points-to-origin/) for the official statement._
