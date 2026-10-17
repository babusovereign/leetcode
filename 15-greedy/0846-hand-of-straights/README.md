# 846. Hand of Straights

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Greedy](../README.md) | [LeetCode 846](https://leetcode.com/problems/hand-of-straights/) |

## Problem

You hold a hand of cards given as an integer array `hand`, and a group size `groupSize`. Decide whether the cards can be split into groups where every group has exactly `groupSize` cards with consecutive values (for example `7, 8, 9`).

Every card must be used in exactly one group. Return `true` if such an arrangement exists, otherwise `false`.

**Implement:** `def isNStraightHand(self, hand: list[int], groupSize: int) -> bool`

## Examples

**Example 1**

```text
Input:  hand = [5, 3, 4, 6, 7, 8], groupSize = 3
Output: true
```

Groups `[3, 4, 5]` and `[6, 7, 8]`.

**Example 2**

```text
Input:  hand = [1, 2, 3, 5], groupSize = 2
Output: false
```

Card `1` must start `[1, 2]`, leaving `3` and `5`, which are not consecutive.

**Example 3**

```text
Input:  hand = [2, 2, 3, 3, 4, 4], groupSize = 3
Output: true
```

Two copies of `[2, 3, 4]`.

## Constraints

- 1 <= hand.length <= 10^4
- 0 <= hand[i] <= 10^9
- 1 <= groupSize <= hand.length

## Notes

- Duplicate card values are allowed.
- This problem is identical to LeetCode 1296 (Divide Array in Sets of K Consecutive Numbers).

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 846](https://leetcode.com/problems/hand-of-straights/) for the official statement._
