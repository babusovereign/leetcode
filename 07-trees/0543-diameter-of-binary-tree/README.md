# 543. Diameter of Binary Tree

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Easy | [Trees](../README.md) | [LeetCode 543](https://leetcode.com/problems/diameter-of-binary-tree/) |

## Problem

Given the `root` of a binary tree, return its diameter: the number of edges on the longest path between any two nodes. That path does not have to pass through the root.

**Implement:** `def diameterOfBinaryTree(self, root: Optional[TreeNode]) -> int`

## Examples

**Example 1**

```text
Input:  root = [8, 3, null, 2, 6, 1, null, null, 7]
Output: 4
```

The longest path is `1 -> 2 -> 3 -> 6 -> 7`, which stays inside the root's left subtree.

**Example 2**

```text
Input:  root = [1]
Output: 0
```

A single node has no edges.

**Example 3**

```text
Input:  root = [1, 2]
Output: 1
```

## Constraints

- The tree has between `1` and `10^4` nodes.
- `-100 <= Node.val <= 100`

## Notes

- Trees are written in level-order with `null` for missing children (e.g. `root = [3, 1, 4, null, 2]`); `[]` is an empty tree.
- Length is counted in edges, not nodes.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 543](https://leetcode.com/problems/diameter-of-binary-tree/) for the official statement._
