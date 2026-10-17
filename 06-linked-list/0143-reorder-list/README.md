# 143. Reorder List

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Linked List](../README.md) | [LeetCode 143](https://leetcode.com/problems/reorder-list/) |

## Problem

Given the `head` of a singly linked list `L0 -> L1 -> ... -> Ln`, rearrange its nodes in place so the order becomes `L0 -> Ln -> L1 -> Ln-1 -> L2 -> Ln-2 -> ...` — alternately taking one node from the front and one from the back.

You must relink the nodes themselves; changing node values is not allowed. The function returns nothing.

**Implement:** `def reorderList(self, head: Optional[ListNode]) -> None`

## Examples

**Example 1**

```text
Input:  head = [10, 20, 30, 40, 50]
Output: [10, 50, 20, 40, 30]
```

Odd length: the middle node ends up last.

**Example 2**

```text
Input:  head = [6, 7, 8, 9]
Output: [6, 9, 7, 8]
```

**Example 3**

```text
Input:  head = [3]
Output: [3]
```

## Constraints

- The list has between `1` and `5 * 10^4` nodes.
- `1 <= Node.val <= 1000`

## Notes

- Lists are written in array notation, head first (e.g. `head = [1, 2, 3]`); `[]` is an empty list.

<details>
<summary>Hint (spoiler)</summary>

- Expected approach: find the middle, reverse the second half, then interleave — O(n) time, O(1) extra space.

</details>

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 143](https://leetcode.com/problems/reorder-list/) for the official statement._
