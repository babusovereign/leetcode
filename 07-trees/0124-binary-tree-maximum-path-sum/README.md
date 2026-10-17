# 124. Binary Tree Maximum Path Sum

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Hard | [Trees](../README.md) | [LeetCode 124](https://leetcode.com/problems/binary-tree-maximum-path-sum/) |

## Problem

A path in a binary tree is any sequence of nodes where each consecutive pair is joined by an edge and no node appears twice; it does not need to go through the root, but it must contain at least one node. A path's sum is the sum of its node values.

Given the `root` of a binary tree, return the largest path sum over all non-empty paths.

**Implement:** `def maxPathSum(self, root: Optional[TreeNode]) -> int`

## Examples

**Example 1**

```text
Input:  root = [2, -1, 5, null, null, 3, -4]
Output: 10
```

Best path is `2 -> 5 -> 3`; including `-1` or `-4` would only lower it.

**Example 2**

```text
Input:  root = [-7]
Output: -7
```

All-negative tree: the answer is the single least-negative node.

**Example 3**

```text
Input:  root = [-2, 6, -3]
Output: 6
```

The single node `6` beats any path through its negative neighbors.

## Constraints

- The tree has between `1` and `3 * 10^4` nodes.
- `-1000 <= Node.val <= 1000`

## Notes

- Trees are written in level-order with `null` for missing children (e.g. `root = [3, 1, 4, null, 2]`); `[]` is an empty tree.
- Values can be negative, so the answer may be negative; don't initialize the running best to `0`.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 124](https://leetcode.com/problems/binary-tree-maximum-path-sum/) for the official statement._
