# 4. Median of Two Sorted Arrays

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Hard | [Binary Search](../README.md) | [LeetCode 4](https://leetcode.com/problems/median-of-two-sorted-arrays/) |

## Problem

Given two arrays `nums1` (length `m`) and `nums2` (length `n`), each sorted in ascending order, return the median of all `m + n` values combined: the middle value if the total count is odd, or the average of the two middle values if it is even. The required time complexity is O(log(m + n)).

**Implement:** `def findMedianSortedArrays(self, nums1: list[int], nums2: list[int]) -> float`

## Examples

**Example 1**

```text
Input:  nums1 = [1, 6, 9], nums2 = [2, 4]
Output: 4.0
```

Merged: `[1, 2, 4, 6, 9]`; the middle value is 4.

**Example 2**

```text
Input:  nums1 = [3, 8], nums2 = [5, 10]
Output: 6.5
```

Merged: `[3, 5, 8, 10]`; the average of 5 and 8.

**Example 3**

```text
Input:  nums1 = [], nums2 = [7]
Output: 7.0
```

One array may be empty.

## Constraints

- 0 <= m, n <= 1000
- 1 <= m + n <= 2000
- -10^6 <= nums1[i], nums2[i] <= 10^6
- O(log(m + n)) time.

## Notes

- Clarify the expected return type: the median is a floating-point value even when it is a whole number.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 4](https://leetcode.com/problems/median-of-two-sorted-arrays/) for the official statement._
