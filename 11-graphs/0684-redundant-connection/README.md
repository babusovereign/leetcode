# 684. Redundant Connection

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Graphs](../README.md) | [LeetCode 684](https://leetcode.com/problems/redundant-connection/) |

## Problem

A tree with `n` nodes labelled `1` to `n` had one extra edge added between two distinct nodes, creating exactly one cycle. You get the resulting `n` edges as `edges[i] = [a, b]` (undirected). Return an edge whose removal turns the graph back into a tree; if several edges qualify, return the one that appears last in `edges`.

**Implement:** `int[] findRedundantConnection(int[][] edges)`

## Examples

**Example 1**

```text
Input:  edges = [[1, 2], [2, 3], [3, 1], [3, 4]]
Output: [3, 1]
```

Edges [1, 2], [2, 3], [3, 1] form a cycle; [3, 1] is the last of them in the input.

**Example 2**

```text
Input:  edges = [[1, 2], [1, 3], [3, 4], [2, 4], [4, 5]]
Output: [2, 4]
```

The cycle is 1-2-4-3-1; removing any of its edges works, and [2, 4] appears last in the input.

**Example 3**

```text
Input:  edges = [[1, 2], [2, 3], [1, 3]]
Output: [1, 3]
```

## Constraints

- 3 <= n <= 1000
- `edges.length == n`
- No repeated edges; the graph is connected.

<details>
<summary>Hint (spoiler)</summary>

- Union-find: the first edge whose endpoints are already connected is the answer.

</details>

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 684](https://leetcode.com/problems/redundant-connection/) for the official statement._
