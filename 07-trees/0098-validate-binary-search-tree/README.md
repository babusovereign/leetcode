# 98. Validate Binary Search Tree

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Trees](../README.md) | [LeetCode 98](https://leetcode.com/problems/validate-binary-search-tree/) |

## Problem

Given the `root` of a binary tree, return `true` if it is a valid binary search tree: for every node, all values in its left subtree are strictly less than it, all values in its right subtree are strictly greater, and both subtrees are themselves valid BSTs.

**Implement:** `def isValidBST(self, root: Optional[TreeNode]) -> bool`

## Examples

**Example 1**

```text
Input:  root = [10, 5, 15, null, null, 12, 20]
Output: true
```

**Example 2**

```text
Input:  root = [10, 5, 15, null, null, 6, 20]
Output: false
```

`6` is the left child of `15` (fine locally), but it sits in the right subtree of `10`, so it must be greater than `10`.

**Example 3**

```text
Input:  root = [3, 3]
Output: false
```

Duplicates are not allowed: the comparison is strict.

## Constraints

- The tree has between `1` and `10^4` nodes.
- `-2^31 <= Node.val <= 2^31 - 1`

## Notes

- Trees are written in level-order with `null` for missing children (e.g. `root = [3, 1, 4, null, 2]`); `[]` is an empty tree.
- Comparing a node only with its direct children is not enough; pass down (low, high) bounds or check that the in-order traversal is strictly increasing.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 98](https://leetcode.com/problems/validate-binary-search-tree/) for the official statement._
