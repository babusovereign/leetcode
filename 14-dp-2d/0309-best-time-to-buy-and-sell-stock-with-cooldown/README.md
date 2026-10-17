# 309. Best Time to Buy and Sell Stock with Cooldown

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [2-D Dynamic Programming](../README.md) | [LeetCode 309](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/) |

## Problem

`prices[i]` is a stock's price on day `i`. You may complete as many buy/sell transactions as you like, but you can hold at most one share at a time, and after selling you must wait one full day (a cooldown) before buying again. Return the maximum total profit.

**Implement:** `def maxProfit(self, prices: list[int]) -> int`

## Examples

**Example 1**

```text
Input:  prices = [2, 5, 1, 4]
Output: 3
```

Buy at 2, sell at 5; the cooldown blocks buying at 1. Buying at 1 and selling at 4 alone also gives 3.

**Example 2**

```text
Input:  prices = [1, 3, 0, 2, 6]
Output: 6
```

e.g. buy 1, sell 3, cooldown, buy 2, sell 6.

**Example 3**

```text
Input:  prices = [3, 2, 1]
Output: 0
```

Edge case: prices only fall, so don't trade.

## Constraints

- 1 <= prices.length <= 5000
- 0 <= prices[i] <= 1000

## Notes

- Model it as a small state machine: holding, just sold (cooling down), and idle.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 309](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/) for the official statement._
