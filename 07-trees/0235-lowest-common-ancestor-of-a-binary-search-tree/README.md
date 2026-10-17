# 235. Lowest Common Ancestor of a BST

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Trees](../README.md) | [LeetCode 235](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/) |

## Problem

Given the `root` of a binary search tree and two of its nodes `p` and `q`, return their lowest common ancestor: the deepest node that has both `p` and `q` as descendants. A node counts as a descendant of itself.

Use the BST ordering to avoid searching both subtrees.

**Implement:** `def lowestCommonAncestor(self, root: TreeNode, p: TreeNode, q: TreeNode) -> TreeNode`

## Examples

**Example 1**

```text
Input:  root = [8, 4, 12, 2, 6, 10, 14, null, null, 5, 7], p = 5, q = 7
Output: 6
```

**Example 2**

```text
Input:  root = [8, 4, 12, 2, 6, 10, 14, null, null, 5, 7], p = 2, q = 7
Output: 4
```

`2` is in the left subtree of `4` and `7` is in the right, so they split at `4`.

**Example 3**

```text
Input:  root = [8, 4, 12, 2, 6, 10, 14, null, null, 5, 7], p = 6, q = 4
Output: 4
```

`4` is an ancestor of `6`, so `4` itself is the answer.

## Constraints

- The tree has between `2` and `10^5` nodes.
- All values are distinct.
- `p != q`, and both exist in the tree.

## Notes

- Trees are written in level-order with `null` for missing children (e.g. `root = [3, 1, 4, null, 2]`); `[]` is an empty tree. `p` and `q` are given by value in the examples; the function receives the node objects.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 235](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/) for the official statement._
