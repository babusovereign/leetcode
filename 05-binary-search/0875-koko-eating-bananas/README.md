# 875. Koko Eating Bananas

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Binary Search](../README.md) | [LeetCode 875](https://leetcode.com/problems/koko-eating-bananas/) |

## Problem

There are `n` piles of bananas, where `piles[i]` is the number of bananas in pile `i`, and a guard returns in `h` hours. Koko picks an integer eating speed `k` (bananas per hour). Each hour she chooses one pile and eats `k` bananas from it; if the pile has fewer than `k`, she finishes it and waits out the rest of that hour without starting another pile. Return the smallest `k` that lets her finish every pile within `h` hours.

**Implement:** `def minEatingSpeed(self, piles: list[int], h: int) -> int`

## Examples

**Example 1**

```text
Input:  piles = [5, 9, 2, 6], h = 7
Output: 5
```

At speed 4 the piles take 2 + 3 + 1 + 2 = 8 hours (too slow); at speed 5 they take 1 + 2 + 1 + 2 = 6 hours.

**Example 2**

```text
Input:  piles = [12], h = 12
Output: 1
```

One banana per hour is enough when `h` equals the pile size.

**Example 3**

```text
Input:  piles = [7, 15, 3], h = 3
Output: 15
```

With exactly one hour per pile, `k` must be at least the largest pile.

## Constraints

- 1 <= piles.length <= 10^4
- piles.length <= h <= 10^9
- 1 <= piles[i] <= 10^9

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 875](https://leetcode.com/problems/koko-eating-bananas/) for the official statement._
