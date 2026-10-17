# 230. Kth Smallest Element in a BST

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Trees](../README.md) | [LeetCode 230](https://leetcode.com/problems/kth-smallest-element-in-a-bst/) |

## Problem

Given the `root` of a binary search tree and an integer `k`, return the `k`-th smallest value in the tree (1-indexed).

Follow-up: if the BST is modified often (inserts and deletes) and you need to query the k-th smallest frequently, how would you optimize?

**Implement:** `def kthSmallest(self, root: Optional[TreeNode], k: int) -> int`

## Examples

**Example 1**

```text
Input:  root = [6, 3, 9, 1, 4, null, null, null, 2], k = 3
Output: 3
```

Sorted values: `1, 2, 3, 4, 6, 9`.

**Example 2**

```text
Input:  root = [6, 3, 9, 1, 4, null, null, null, 2], k = 6
Output: 9
```

`k` equal to the node count gives the maximum.

**Example 3**

```text
Input:  root = [5], k = 1
Output: 5
```

## Constraints

- The tree has `n` nodes, `1 <= k <= n <= 10^4`.
- `0 <= Node.val <= 10^4`

## Notes

- Trees are written in level-order with `null` for missing children (e.g. `root = [3, 1, 4, null, 2]`); `[]` is an empty tree.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 230](https://leetcode.com/problems/kth-smallest-element-in-a-bst/) for the official statement._
