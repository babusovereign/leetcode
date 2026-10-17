# 133. Clone Graph

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Graphs](../README.md) | [LeetCode 133](https://leetcode.com/problems/clone-graph/) |

## Problem

Given a reference to one node of a connected, undirected graph, return a deep copy of the whole graph. Each node has an integer `val` and a list `neighbors`. Node values are `1..n` and unique, and the given node is the one with value `1`. In examples the graph is written as an adjacency list where entry `i` (1-based) lists the neighbours of node `i`; the output must have identical structure, but none of the returned nodes may be objects from the original graph.

**Implement:** `Node cloneGraph(Node node)`

## Examples

**Example 1**

```text
Input:  adjList = [[2, 3], [1, 3], [1, 2]]
Output: [[2, 3], [1, 3], [1, 2]]
```

A triangle of 3 nodes; the copy has the same shape but entirely new node objects.

**Example 2**

```text
Input:  adjList = [[]]
Output: [[]]
```

A single node with no neighbours.

**Example 3**

```text
Input:  adjList = []
Output: []
```

An empty graph (null input) returns null.

## Constraints

- 0 <= number of nodes <= 100
- Node values are unique, from `1` to `n`.
- No self-loops or repeated edges; the graph is connected.

## Notes

- Cycles are expected; a map from original node to clone prevents infinite recursion.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 133](https://leetcode.com/problems/clone-graph/) for the official statement._
