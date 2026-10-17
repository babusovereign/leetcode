# 226. Invert Binary Tree

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Easy | [Trees](../README.md) | [LeetCode 226](https://leetcode.com/problems/invert-binary-tree/) |

## Problem

Given the `root` of a binary tree, mirror it: at every node, swap the left and right subtrees. Return the root of the mirrored tree.

**Implement:** `def invertTree(self, root: Optional[TreeNode]) -> Optional[TreeNode]`

## Examples

**Example 1**

```text
Input:  root = [5, 3, 8, 1, 4, null, 9]
Output: [5, 8, 3, 9, null, 4, 1]
```

**Example 2**

```text
Input:  root = []
Output: []
```

**Example 3**

```text
Input:  root = [2, 1]
Output: [2, null, 1]
```

The lone left child becomes a right child.

## Constraints

- The tree has between `0` and `100` nodes.
- `-100 <= Node.val <= 100`

## Notes

- Trees are written in level-order with `null` for missing children (e.g. `root = [3, 1, 4, null, 2]`); `[]` is an empty tree.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 226](https://leetcode.com/problems/invert-binary-tree/) for the official statement._
