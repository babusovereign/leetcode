# 287. Find the Duplicate Number

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Linked List](../README.md) | [LeetCode 287](https://leetcode.com/problems/find-the-duplicate-number/) |

## Problem

You are given an array `nums` of `n + 1` integers where every value lies in the range `[1, n]`. By the pigeonhole principle at least one value repeats; it is guaranteed that exactly one distinct value is repeated (it may appear two or more times). Return that value.

You may not modify `nums`, and you must use only O(1) extra space.

**Implement:** `def findDuplicate(self, nums: list[int]) -> int`

## Examples

**Example 1**

```text
Input:  nums = [2, 5, 1, 3, 5, 4]
Output: 5
```

**Example 2**

```text
Input:  nums = [1, 1]
Output: 1
```

Smallest possible input (`n = 1`).

**Example 3**

```text
Input:  nums = [3, 3, 3, 1]
Output: 3
```

The duplicate may appear more than twice.

## Constraints

- `1 <= n <= 10^5`
- `nums.length == n + 1`
- `1 <= nums[i] <= n`
- Exactly one value is repeated, possibly more than twice.

## Notes

- This is in the linked-list unit because treating `i -> nums[i]` as a `next` pointer produces a cycle whose entry is the duplicate (Floyd's algorithm).
- Sorting or a hash set would violate the no-modify / O(1)-space requirements.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 287](https://leetcode.com/problems/find-the-duplicate-number/) for the official statement._
