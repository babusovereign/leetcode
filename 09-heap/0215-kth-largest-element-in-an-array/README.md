# 215. Kth Largest Element in an Array

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Heap / Priority Queue](../README.md) | [LeetCode 215](https://leetcode.com/problems/kth-largest-element-in-an-array/) |

## Problem

Given an integer array `nums` and an integer `k`, return the `k`-th largest element, meaning the element that would be at position `k` (1-based) if the array were sorted in descending order. Duplicates are counted, so this is not the k-th largest *distinct* value. Aim to do better than a full sort.

**Implement:** `int findKthLargest(int[] nums, int k)`

## Examples

**Example 1**

```text
Input:  nums = [7, 2, 9, 4, 9, 1], k = 2
Output: 9
```

Sorted descending: [9, 9, 7, 4, 2, 1]; duplicates count separately, so the 2nd largest is 9.

**Example 2**

```text
Input:  nums = [-5, -1, -3], k = 3
Output: -5
```

**Example 3**

```text
Input:  nums = [42], k = 1
Output: 42
```

## Constraints

- 1 <= k <= nums.length <= 10^5
- -10^4 <= nums[i] <= 10^4

<details>
<summary>Hint (spoiler)</summary>

- A size-k min-heap gives O(n log k); quickselect gives average O(n).

</details>

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 215](https://leetcode.com/problems/kth-largest-element-in-an-array/) for the official statement._
