# 199. Binary Tree Right Side View

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Trees](../README.md) | [LeetCode 199](https://leetcode.com/problems/binary-tree-right-side-view/) |

## Problem

Imagine standing to the right of a binary tree. Given its `root`, return the values of the nodes you can see, from top to bottom — that is, the rightmost node at each depth.

**Implement:** `def rightSideView(self, root: Optional[TreeNode]) -> list[int]`

## Examples

**Example 1**

```text
Input:  root = [7, 3, 9, 2, null, null, null, 1]
Output: [7, 9, 2, 1]
```

The deeper levels exist only on the left side, so left-subtree nodes `2` and `1` are visible.

**Example 2**

```text
Input:  root = []
Output: []
```

**Example 3**

```text
Input:  root = [5, 6]
Output: [5, 6]
```

`6` is a left child but is still the only node at depth 1.

## Constraints

- The tree has between `0` and `100` nodes.
- `-100 <= Node.val <= 100`

## Notes

- Trees are written in level-order with `null` for missing children (e.g. `root = [3, 1, 4, null, 2]`); `[]` is an empty tree.
- The visible node is not always in the right subtree.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 199](https://leetcode.com/problems/binary-tree-right-side-view/) for the official statement._
