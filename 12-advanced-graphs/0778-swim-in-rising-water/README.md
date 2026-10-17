# 778. Swim in Rising Water

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Hard | [Advanced Graphs](../README.md) | [LeetCode 778](https://leetcode.com/problems/swim-in-rising-water/) |

## Problem

You are given an `n x n` grid where `grid[r][c]` is the elevation of that cell. Rain falls so that at time `t` the water level everywhere is `t`. You can move instantly between 4-directionally adjacent cells, but only if both cells have elevation at most `t`. Starting at the top-left cell `(0, 0)`, return the earliest time at which you can reach the bottom-right cell `(n - 1, n - 1)`.

**Implement:** `int swimInWater(int[][] grid)`

## Examples

**Example 1**

```text
Input:  grid = [[0, 3], [1, 2]]
Output: 2
```

At time 2 the path (0,0) -> (1,0) -> (1,1) is open; the destination itself has elevation 2.

**Example 2**

```text
Input:  grid = [[0, 8, 7], [1, 6, 2], [3, 4, 5]]
Output: 5
```

The route down the left column and along the bottom row never exceeds elevation 5.

**Example 3**

```text
Input:  grid = [[0]]
Output: 0
```

Start and destination are the same cell.

## Constraints

- 1 <= n <= 50
- The grid values are a permutation of `0` to `n^2 - 1` (all distinct).

<details>
<summary>Hint (spoiler)</summary>

- Equivalently: minimise the maximum elevation along a path. Dijkstra with a max-based cost, or binary search plus BFS, both work.

</details>

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 778](https://leetcode.com/problems/swim-in-rising-water/) for the official statement._
