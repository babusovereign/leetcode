# 19. Remove Nth Node From End of List

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Linked List](../README.md) | [LeetCode 19](https://leetcode.com/problems/remove-nth-node-from-end-of-list/) |

## Problem

Given the `head` of a singly linked list and an integer `n`, delete the `n`-th node counting from the end of the list (`n = 1` is the last node) and return the head of the resulting list.

A follow-up asks you to do it in a single pass.

**Implement:** `def removeNthFromEnd(self, head: Optional[ListNode], n: int) -> Optional[ListNode]`

## Examples

**Example 1**

```text
Input:  head = [3, 6, 9, 12], n = 3
Output: [3, 9, 12]
```

The 3rd node from the end is `6`.

**Example 2**

```text
Input:  head = [7], n = 1
Output: []
```

Removing the only node leaves an empty list.

**Example 3**

```text
Input:  head = [2, 5], n = 1
Output: [2]
```

## Constraints

- The list has `sz` nodes, `1 <= sz <= 30`.
- `0 <= Node.val <= 100`
- `1 <= n <= sz`

## Notes

- Lists are written in array notation, head first (e.g. `head = [1, 2, 3]`); `[]` is an empty list.
- Removing the head itself must be handled — a dummy node before the head simplifies this.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 19](https://leetcode.com/problems/remove-nth-node-from-end-of-list/) for the official statement._
