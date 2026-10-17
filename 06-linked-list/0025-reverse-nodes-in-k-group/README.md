# 25. Reverse Nodes in k-Group

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Hard | [Linked List](../README.md) | [LeetCode 25](https://leetcode.com/problems/reverse-nodes-in-k-group/) |

## Problem

Given the `head` of a linked list and a positive integer `k`, reverse the nodes in consecutive groups of `k` and return the new head. If the final group has fewer than `k` nodes, leave it in its original order.

You must relink nodes rather than swap values. The follow-up asks for O(1) extra space.

**Implement:** `def reverseKGroup(self, head: Optional[ListNode], k: int) -> Optional[ListNode]`

## Examples

**Example 1**

```text
Input:  head = [1, 2, 3, 4, 5, 6, 7], k = 3
Output: [3, 2, 1, 6, 5, 4, 7]
```

Two full groups of 3 are reversed; the leftover `7` stays put.

**Example 2**

```text
Input:  head = [10, 20, 30, 40, 50], k = 2
Output: [20, 10, 40, 30, 50]
```

The trailing `50` is a partial group and is untouched.

**Example 3**

```text
Input:  head = [5, 6], k = 1
Output: [5, 6]
```

`k = 1` leaves the list unchanged.

## Constraints

- The list has `n` nodes, `1 <= k <= n <= 5000`.
- `0 <= Node.val <= 1000`

## Notes

- Lists are written in array notation, head first (e.g. `head = [1, 2, 3]`); `[]` is an empty list.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 25](https://leetcode.com/problems/reverse-nodes-in-k-group/) for the official statement._
