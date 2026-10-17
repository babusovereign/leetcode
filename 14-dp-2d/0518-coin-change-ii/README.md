# 518. Coin Change II

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [2-D Dynamic Programming](../README.md) | [LeetCode 518](https://leetcode.com/problems/coin-change-ii/) |

## Problem

Given an `amount` and an array `coins` of distinct denominations (unlimited supply of each), return the number of different combinations of coins that sum to `amount`. Combinations are unordered, so `1 + 2` and `2 + 1` are the same. If no combination works, return `0`.

**Implement:** `def change(self, amount: int, coins: list[int]) -> int`

## Examples

**Example 1**

```text
Input:  amount = 6, coins = [1, 2, 5]
Output: 5
```

1x6, 1x4+2, 1x2+2x2, 2x3, 1+5.

**Example 2**

```text
Input:  amount = 4, coins = [3]
Output: 0
```

**Example 3**

```text
Input:  amount = 0, coins = [2, 7]
Output: 1
```

Edge case: the empty combination counts once.

## Constraints

- 1 <= coins.length <= 300
- 1 <= coins[i] <= 5000
- All coin values are distinct.
- 0 <= amount <= 5000
- The answer fits in a signed 32-bit integer.

## Notes

- Loop over coins in the outer loop to count combinations rather than permutations.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 518](https://leetcode.com/problems/coin-change-ii/) for the official statement._
