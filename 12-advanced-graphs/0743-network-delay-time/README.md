# 743. Network Delay Time

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Advanced Graphs](../README.md) | [LeetCode 743](https://leetcode.com/problems/network-delay-time/) |

## Problem

A network has `n` nodes labelled `1` to `n`. You are given directed, weighted edges `times[i] = [u, v, w]`, meaning a signal sent from `u` reaches `v` after `w` time units. A signal is sent from node `k`. Return the time it takes for every node to receive it (that is, the largest shortest-path distance from `k`), or `-1` if some node can never receive it.

**Implement:** `int networkDelayTime(int[][] times, int n, int k)`

## Examples

**Example 1**

```text
Input:  times = [[1, 2, 4], [1, 3, 1], [3, 2, 2], [2, 4, 5]], n = 4, k = 1
Output: 8
```

Node 2 is reached fastest via 1 -> 3 -> 2 (time 3), so node 4 hears it at 3 + 5 = 8.

**Example 2**

```text
Input:  times = [[1, 2, 3]], n = 2, k = 2
Output: -1
```

Edges are directed; node 1 can never be reached from node 2.

**Example 3**

```text
Input:  times = [[2, 1, 7]], n = 2, k = 2
Output: 7
```

## Constraints

- 1 <= k <= n <= 100
- 1 <= times.length <= 6000
- 0 <= w <= 100
- No duplicate `(u, v)` pairs and no self-loops.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 743](https://leetcode.com/problems/network-delay-time/) for the official statement._
