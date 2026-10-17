# 286. Walls and Gates

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Graphs](../README.md) | [LeetCode 286](https://leetcode.com/problems/walls-and-gates/) (Premium) |

> LeetCode Premium. The same problem is free to practise on [NeetCode](https://neetcode.io/practice).

## Problem

You are given an `m x n` grid `rooms` where `-1` is a wall, `0` is a gate, and `INF` (the value `2147483647`, i.e. `2^31 - 1`) is an empty room. Fill each empty room in place with the number of steps to its nearest gate, moving only up, down, left, or right and never through walls. Rooms that cannot reach any gate keep the value `INF`. The method returns nothing; it modifies `rooms`.

**Implement:** `void wallsAndGates(int[][] rooms)`

## Examples

**Example 1**

```text
Input:  rooms = [[INF, -1, 0], [INF, INF, INF], [0, -1, INF]]
Output: [[2, -1, 0], [1, 2, 1], [0, -1, 2]]
```

Each empty room is filled with its step distance to the closest gate.

**Example 2**

```text
Input:  rooms = [[INF, -1], [-1, 0]]
Output: [[INF, -1], [-1, 0]]
```

The top-left room is walled off from every gate, so it stays INF.

## Constraints

- 1 <= m, n <= 250
- Each cell is `-1`, `0`, or `2^31 - 1`.

<details>
<summary>Hint (spoiler)</summary>

- A multi-source BFS starting from all gates at once visits each cell once.

</details>

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 286](https://leetcode.com/problems/walls-and-gates/) for the official statement._
