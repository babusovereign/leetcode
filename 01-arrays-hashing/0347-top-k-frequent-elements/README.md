# 347. Top K Frequent Elements

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Arrays & Hashing](../README.md) | [LeetCode 347](https://leetcode.com/problems/top-k-frequent-elements/) |

## Problem

Given an integer array `nums` and an integer `k`, return the `k` values that occur most often in `nums`. The answer may be in any order, and the input guarantees the top `k` set is unambiguous (no tie at the cutoff).

**Implement:** `def topKFrequent(self, nums: list[int], k: int) -> list[int]`

## Examples

**Example 1**

```text
Input:  nums = [5, 7, 5, 9, 7, 5], k = 2
Output: [5, 7] (any order)
```

`5` appears 3 times, `7` twice, `9` once.

**Example 2**

```text
Input:  nums = [-4], k = 1
Output: [-4]
```

**Example 3**

```text
Input:  nums = [2, 3, 3, 1, 1, 1], k = 3
Output: [1, 2, 3] (any order)
```

When `k` equals the number of distinct values, every value is returned.

## Constraints

- 1 <= nums.length <= 10^5
- `k` is between 1 and the number of distinct values in `nums`.
- The answer is unique.

## Notes

- Follow-up: aim for better than O(n log n) time.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 347](https://leetcode.com/problems/top-k-frequent-elements/) for the official statement._
