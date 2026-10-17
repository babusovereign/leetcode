# 787. Cheapest Flights Within K Stops

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Advanced Graphs](../README.md) | [LeetCode 787](https://leetcode.com/problems/cheapest-flights-within-k-stops/) |

## Problem

There are `n` cities labelled `0` to `n - 1` and a list of one-way `flights[i] = [from, to, price]`. Given a source `src`, destination `dst`, and integer `k`, return the cheapest total price to fly from `src` to `dst` using at most `k` intermediate stops (that is, at most `k + 1` flights). Return `-1` if no such route exists.

**Implement:** `int findCheapestPrice(int n, int[][] flights, int src, int dst, int k)`

## Examples

**Example 1**

```text
Input:  n = 4, flights = [[0, 1, 100], [1, 2, 100], [2, 3, 100], [0, 3, 500], [0, 2, 250]], src = 0, dst = 3, k = 1
Output: 350
```

With at most one stop, the best route is 0 -> 2 -> 3.

**Example 2**

```text
Input:  n = 4, flights = [[0, 1, 100], [1, 2, 100], [2, 3, 100], [0, 3, 500], [0, 2, 250]], src = 0, dst = 3, k = 2
Output: 300
```

Allowing two stops makes 0 -> 1 -> 2 -> 3 possible.

**Example 3**

```text
Input:  n = 3, flights = [[0, 1, 50], [1, 2, 50]], src = 0, dst = 2, k = 0
Output: -1
```

With zero stops a direct flight is required, and none exists.

## Constraints

- 1 <= n <= 100
- Prices are positive integers.
- No duplicate flights and no self-loops.
- 0 <= src, dst, k < n
- `src != dst`

<details>
<summary>Hint (spoiler)</summary>

- Plain Dijkstra on cost alone is wrong because a cheaper path may use too many stops; Bellman-Ford limited to `k + 1` rounds is a clean approach.

</details>

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 787](https://leetcode.com/problems/cheapest-flights-within-k-stops/) for the official statement._
