# 23. Merge k Sorted Lists

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Hard | [Linked List](../README.md) | [LeetCode 23](https://leetcode.com/problems/merge-k-sorted-lists/) |

## Problem

You are given an array `lists` of `k` linked lists, each sorted in ascending order. Merge all of them into a single sorted linked list and return its head.

A good solution runs in O(N log k), where `N` is the total number of nodes — via a min-heap or by merging lists in pairs.

**Implement:** `def mergeKLists(self, lists: list[Optional[ListNode]]) -> Optional[ListNode]`

## Examples

**Example 1**

```text
Input:  lists = [[2, 6, 8], [1, 3, 7], [5]]
Output: [1, 2, 3, 5, 6, 7, 8]
```

**Example 2**

```text
Input:  lists = []
Output: []
```

No lists at all.

**Example 3**

```text
Input:  lists = [[], [4]]
Output: [4]
```

Some of the lists may be empty.

## Constraints

- `0 <= k <= 10^4`
- Each list has between `0` and `500` nodes.
- `-10^4 <= Node.val <= 10^4`
- Each list is sorted ascending; the total number of nodes is at most `10^4`.

## Notes

- Lists are written in array notation, head first (e.g. `head = [1, 2, 3]`); `[]` is an empty list.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 23](https://leetcode.com/problems/merge-k-sorted-lists/) for the official statement._
