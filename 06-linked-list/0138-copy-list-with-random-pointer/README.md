# 138. Copy List with Random Pointer

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Linked List](../README.md) | [LeetCode 138](https://leetcode.com/problems/copy-list-with-random-pointer/) |

## Problem

Each node in a linked list of length `n` has a `next` pointer and an extra `random` pointer, which may point to any node in the list or be `null`. Build a deep copy: `n` brand-new nodes with the same values, where every copied `next` and `random` pointer refers to the corresponding new node. No pointer in the copy may reference an original node.

Return the head of the copied list.

**Implement:** `def copyRandomList(self, head: Optional[Node]) -> Optional[Node]`

## Examples

**Example 1**

```text
Input:  head = [[5, null], [9, 0], [1, 1]]
Output: [[5, null], [9, 0], [1, 1]]
```

Same shape as the input, but every node is new: node 1's random points to the new node 0, node 2's to the new node 1.

**Example 2**

```text
Input:  head = []
Output: []
```

**Example 3**

```text
Input:  head = [[4, 0]]
Output: [[4, 0]]
```

A single node whose `random` points to itself.

## Constraints

- `0 <= n <= 1000`
- `-10^4 <= Node.val <= 10^4`
- `random` is `null` or points to a node in the same list.

## Notes

- Notation: each node is written as `[val, random_index]`, where `random_index` is the 0-based position of the node its `random` points to, or `null`.

<details>
<summary>Hint (spoiler)</summary>

- Approaches: a hash map from old node to new node (O(n) space), or interleaving copies into the original list (O(1) extra space).

</details>

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 138](https://leetcode.com/problems/copy-list-with-random-pointer/) for the official statement._
