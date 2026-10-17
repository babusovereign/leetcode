# 417. Pacific Atlantic Water Flow

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Graphs](../README.md) | [LeetCode 417](https://leetcode.com/problems/pacific-atlantic-water-flow/) |

## Problem

An `m x n` island is described by a matrix `heights` of cell elevations. The Pacific Ocean touches the island's top and left edges, and the Atlantic Ocean touches its bottom and right edges. Rain on a cell can flow to a 4-directionally adjacent cell whose height is less than or equal to the current one, and from any edge cell directly into the ocean bordering that edge. Return the coordinates `[r, c]` of every cell from which water can reach both oceans, in any order.

**Implement:** `List<List<Integer>> pacificAtlantic(int[][] heights)`

## Examples

**Example 1**

```text
Input:  heights = [[1, 2, 3], [8, 9, 4], [7, 6, 5]]
Output: [[0, 2], [1, 0], [1, 1], [1, 2], [2, 0], [2, 1], [2, 2]] (any order)
```

**Example 2**

```text
Input:  heights = [[4]]
Output: [[0, 0]]
```

A single cell touches both oceans.

**Example 3**

```text
Input:  heights = [[2, 2], [2, 2]]
Output: [[0, 0], [0, 1], [1, 0], [1, 1]] (any order)
```

Water can flow between cells of equal height, so every cell reaches both oceans.

## Constraints

- 1 <= m, n <= 200
- 0 <= heights[r][c] <= 10^5

<details>
<summary>Hint (spoiler)</summary>

- Searching uphill from each ocean's border is far cheaper than searching from every cell.

</details>

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 417](https://leetcode.com/problems/pacific-atlantic-water-flow/) for the official statement._
