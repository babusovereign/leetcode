# 322. Coin Change

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [1-D Dynamic Programming](../README.md) | [LeetCode 322](https://leetcode.com/problems/coin-change/) |

## Problem

You have unlimited coins of each denomination in `coins` and a target `amount`. Return the fewest coins whose values add up to exactly `amount`, or `-1` if that amount cannot be formed. An `amount` of `0` needs zero coins.

**Implement:** `def coinChange(self, coins: list[int], amount: int) -> int`

## Examples

**Example 1**

```text
Input:  coins = [1, 4, 5], amount = 8
Output: 2
```

4 + 4. Greedy (5 + 1 + 1 + 1) would use 4 coins.

**Example 2**

```text
Input:  coins = [3], amount = 7
Output: -1
```

7 is not a multiple of 3.

**Example 3**

```text
Input:  coins = [2], amount = 0
Output: 0
```

Edge case: nothing to pay.

## Constraints

- 1 <= coins.length <= 12
- 1 <= coins[i] <= 2^31 - 1
- 0 <= amount <= 10^4

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 322](https://leetcode.com/problems/coin-change/) for the official statement._
