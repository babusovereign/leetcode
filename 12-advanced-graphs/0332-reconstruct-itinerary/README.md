# 332. Reconstruct Itinerary

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Hard | [Advanced Graphs](../README.md) | [LeetCode 332](https://leetcode.com/problems/reconstruct-itinerary/) |

## Problem

You are given a list of airline `tickets`, each `[from, to]` with three-letter airport codes. Reconstruct a travel itinerary that starts at `"JFK"` and uses every ticket exactly once. If several valid itineraries exist, return the one that is smallest in lexical order when compared as a sequence of airport codes. At least one valid itinerary is guaranteed to exist.

**Implement:** `List<String> findItinerary(List<List<String>> tickets)`

## Examples

**Example 1**

```text
Input:  tickets = [["JFK", "SEA"], ["SEA", "JFK"], ["JFK", "BOS"], ["BOS", "JFK"]]
Output: ["JFK", "BOS", "JFK", "SEA", "JFK"]
```

Both JFK -> BOS ... and JFK -> SEA ... use all tickets; the BOS-first route is lexicographically smaller.

**Example 2**

```text
Input:  tickets = [["JFK", "MIA"], ["JFK", "ATL"], ["ATL", "JFK"]]
Output: ["JFK", "ATL", "JFK", "MIA"]
```

Going to ATL first is smaller, and it is also the only order that uses every ticket, since MIA is a dead end.

**Example 3**

```text
Input:  tickets = [["LAX", "DEN"], ["JFK", "LAX"]]
Output: ["JFK", "LAX", "DEN"]
```

## Constraints

- 1 <= tickets.length <= 300
- Airport codes are three uppercase letters.
- Tickets may repeat; every ticket must be used exactly once.
- A valid itinerary using all tickets always exists.

## Notes

- Greedily picking the smallest next airport alone can strand you; Hierholzer's algorithm handles dead ends.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 332](https://leetcode.com/problems/reconstruct-itinerary/) for the official statement._
