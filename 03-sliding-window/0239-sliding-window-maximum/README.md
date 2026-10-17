# 239. Sliding Window Maximum

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Hard | [Sliding Window](../README.md) | [LeetCode 239](https://leetcode.com/problems/sliding-window-maximum/) |

## Problem

Given an integer array `nums` and a window size `k`, slide a window of exactly `k` consecutive elements from the left end of the array to the right end, one position at a time. Return an array containing the maximum value inside the window at each position (so the result has `nums.length - k + 1` entries).

**Implement:** `def maxSlidingWindow(self, nums: list[int], k: int) -> list[int]`

## Examples

**Example 1**

```text
Input:  nums = [2, -1, 4, 0, 3, 3, -5], k = 3
Output: [4, 4, 4, 3, 3]
```

Windows: `[2,-1,4]`, `[-1,4,0]`, `[4,0,3]`, `[0,3,3]`, `[3,3,-5]`.

**Example 2**

```text
Input:  nums = [6, 2], k = 1
Output: [6, 2]
```

With `k = 1` each element is its own window.

**Example 3**

```text
Input:  nums = [1, 9, 4], k = 3
Output: [9]
```

## Constraints

- 1 <= nums.length <= 10^5
- -10^4 <= nums[i] <= 10^4
- 1 <= k <= nums.length

## Notes

- Aim for O(n) overall rather than O(n * k).

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 239](https://leetcode.com/problems/sliding-window-maximum/) for the official statement._
