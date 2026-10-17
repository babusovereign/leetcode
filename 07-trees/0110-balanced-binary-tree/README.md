# 110. Balanced Binary Tree

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Easy | [Trees](../README.md) | [LeetCode 110](https://leetcode.com/problems/balanced-binary-tree/) |

## Problem

Given the `root` of a binary tree, return `true` if it is height-balanced: for every node, the heights of its left and right subtrees differ by at most `1`. Otherwise return `false`.

**Implement:** `def isBalanced(self, root: Optional[TreeNode]) -> bool`

## Examples

**Example 1**

```text
Input:  root = [4, 2, 6, 1, 3, 5, 7]
Output: true
```

**Example 2**

```text
Input:  root = [1, 2, null, 3]
Output: false
```

At the root, the left subtree has height 2 and the right has height 0.

**Example 3**

```text
Input:  root = []
Output: true
```

An empty tree is balanced.

## Constraints

- The tree has between `0` and `5000` nodes.
- `-10^4 <= Node.val <= 10^4`

## Notes

- Trees are written in level-order with `null` for missing children (e.g. `root = [3, 1, 4, null, 2]`); `[]` is an empty tree.
- The check applies at every node, not just the root. An O(n) solution returns height and balance together in one post-order pass.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 110](https://leetcode.com/problems/balanced-binary-tree/) for the official statement._
