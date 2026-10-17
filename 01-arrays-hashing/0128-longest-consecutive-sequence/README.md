# 128. Longest Consecutive Sequence

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Arrays & Hashing](../README.md) | [LeetCode 128](https://leetcode.com/problems/longest-consecutive-sequence/) |

## Problem

Given an unsorted integer array `nums`, return the length of the longest run of consecutive integers (values `x, x+1, x+2, ...`) whose members all appear somewhere in `nums`. The elements do not need to be adjacent in the array, and duplicates count only once. The intended solution runs in O(n) time.

**Implement:** `def longestConsecutive(self, nums: list[int]) -> int`

## Examples

**Example 1**

```text
Input:  nums = [10, 4, 12, 3, 11, 5, 2]
Output: 4
```

The run `2, 3, 4, 5` has length 4; `10, 11, 12` has length 3.

**Example 2**

```text
Input:  nums = [7, 7, 8, -1, 0]
Output: 2
```

Both `7, 8` and `-1, 0` have length 2; the repeated `7` is counted once.

**Example 3**

```text
Input:  nums = []
Output: 0
```

## Constraints

- 0 <= nums.length <= 10^5
- -10^9 <= nums[i] <= 10^9
- Required time complexity: O(n).

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 128](https://leetcode.com/problems/longest-consecutive-sequence/) for the official statement._
