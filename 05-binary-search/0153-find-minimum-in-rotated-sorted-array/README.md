# 153. Find Minimum in Rotated Sorted Array

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Binary Search](../README.md) | [LeetCode 153](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) |

## Problem

A sorted array of distinct integers has been rotated some number of times (between 1 and `n`), meaning a suffix of it was moved to the front, e.g. `[1, 2, 3, 4, 5]` could become `[4, 5, 1, 2, 3]`; rotating `n` times gives back the original order. Given the rotated array `nums`, return its minimum element in O(log n) time.

**Implement:** `def findMin(self, nums: list[int]) -> int`

## Examples

**Example 1**

```text
Input:  nums = [15, 18, 22, 3, 7, 10]
Output: 3
```

**Example 2**

```text
Input:  nums = [2, 4, 6, 8]
Output: 2
```

The array was rotated a full cycle, so it is fully sorted.

**Example 3**

```text
Input:  nums = [9, -1]
Output: -1
```

## Constraints

- 1 <= nums.length <= 5000
- -5000 <= nums[i] <= 5000
- All values are distinct.
- `nums` is a rotated ascending array.
- O(log n) time.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 153](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) for the official statement._
