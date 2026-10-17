# 2. Add Two Numbers

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Linked List](../README.md) | [LeetCode 2](https://leetcode.com/problems/add-two-numbers/) |

## Problem

Two non-negative integers are given as non-empty linked lists `l1` and `l2`, with digits stored in reverse order (the ones digit is at the head) and one digit per node. Return their sum as a linked list in the same reverse-digit format.

Neither number has leading zeros, except the number `0` itself.

**Implement:** `def addTwoNumbers(self, l1: Optional[ListNode], l2: Optional[ListNode]) -> Optional[ListNode]`

## Examples

**Example 1**

```text
Input:  l1 = [4, 6, 1], l2 = [8, 5]
Output: [2, 2, 2]
```

`164 + 58 = 222`.

**Example 2**

```text
Input:  l1 = [9, 9, 9], l2 = [1]
Output: [0, 0, 0, 1]
```

`999 + 1 = 1000`: the final carry adds a new node.

**Example 3**

```text
Input:  l1 = [0], l2 = [0]
Output: [0]
```

## Constraints

- Each list has between `1` and `100` nodes.
- `0 <= Node.val <= 9`
- No leading zeros except for the number `0`.

## Notes

- Lists are written in array notation, head first (e.g. `head = [1, 2, 3]`); `[]` is an empty list.
- Lists can have different lengths, and a carry may remain after both are exhausted.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 2](https://leetcode.com/problems/add-two-numbers/) for the official statement._
