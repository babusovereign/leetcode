# 141. Linked List Cycle

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Easy | [Linked List](../README.md) | [LeetCode 141](https://leetcode.com/problems/linked-list-cycle/) |

## Problem

Given the `head` of a singly linked list, return `true` if following `next` pointers ever revisits a node (i.e., the list contains a cycle), and `false` if the traversal eventually reaches `null`.

The follow-up asks for O(1) extra memory.

**Implement:** `def hasCycle(self, head: Optional[ListNode]) -> bool`

## Examples

**Example 1**

```text
Input:  head = [2, 7, 4, 9], pos = 1
Output: true
```

The last node links back to the node at index 1 (`7`).

**Example 2**

```text
Input:  head = [5], pos = -1
Output: false
```

`pos = -1` means no cycle.

**Example 3**

```text
Input:  head = [1, 2], pos = 0
Output: true
```

The tail links back to the head.

## Constraints

- The list has between `0` and `10^4` nodes.
- `-10^5 <= Node.val <= 10^5`

## Notes

- Lists are written in array notation, head first (e.g. `head = [1, 2, 3]`); `[]` is an empty list. `pos` is only used to describe the test input: it is the index the tail's `next` points to (`-1` for none) and is not passed to the function.

<details>
<summary>Hint (spoiler)</summary>

- Classic approach: Floyd's slow/fast pointers.

</details>

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 141](https://leetcode.com/problems/linked-list-cycle/) for the official statement._
