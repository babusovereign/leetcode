# 1046. Last Stone Weight

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Easy | [Heap / Priority Queue](../README.md) | [LeetCode 1046](https://leetcode.com/problems/last-stone-weight/) |

## Problem

You have a pile of stones with positive integer weights. Repeatedly pick the two heaviest stones, with weights `x <= y`, and smash them together: if `x == y` both are destroyed, otherwise the lighter one is destroyed and the heavier one's weight becomes `y - x`. Stop when at most one stone remains, and return its weight, or `0` if no stones are left.

**Implement:** `int lastStoneWeight(int[] stones)`

## Examples

**Example 1**

```text
Input:  stones = [3, 7, 2, 2]
Output: 0
```

Smash 7 and 3 -> 4; smash 4 and 2 -> 2; smash 2 and 2 -> nothing left.

**Example 2**

```text
Input:  stones = [10, 4, 5]
Output: 1
```

**Example 3**

```text
Input:  stones = [6]
Output: 6
```

A single stone is never smashed.

## Constraints

- 1 <= stones.length <= 30
- 1 <= stones[i] <= 1000

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 1046](https://leetcode.com/problems/last-stone-weight/) for the official statement._
