# 21. Merge Two Sorted Lists

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Easy | [Linked List](../README.md) | [LeetCode 21](https://leetcode.com/problems/merge-two-sorted-lists/) |

## Problem

You are given the heads of two singly linked lists, `list1` and `list2`, each already sorted in non-decreasing order. Combine them into one sorted list by relinking the existing nodes (not by creating new ones) and return its head.

**Implement:** `def mergeTwoLists(self, list1: Optional[ListNode], list2: Optional[ListNode]) -> Optional[ListNode]`

## Examples

**Example 1**

```text
Input:  list1 = [1, 4, 9], list2 = [2, 4, 10]
Output: [1, 2, 4, 4, 9, 10]
```

Equal values (`4`) may come from either list.

**Example 2**

```text
Input:  list1 = [], list2 = [0]
Output: [0]
```

**Example 3**

```text
Input:  list1 = [], list2 = []
Output: []
```

Both inputs empty.

## Constraints

- Each list has between `0` and `50` nodes.
- `-100 <= Node.val <= 100`
- Both lists are sorted in non-decreasing order.

## Notes

- Lists are written in array notation, head first (e.g. `head = [1, 2, 3]`); `[]` is an empty list.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 21](https://leetcode.com/problems/merge-two-sorted-lists/) for the official statement._
