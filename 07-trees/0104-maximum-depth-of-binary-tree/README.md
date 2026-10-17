# 104. Maximum Depth of Binary Tree

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Easy | [Trees](../README.md) | [LeetCode 104](https://leetcode.com/problems/maximum-depth-of-binary-tree/) |

## Problem

Given the `root` of a binary tree, return its maximum depth: the number of nodes on the longest path from the root down to any leaf. An empty tree has depth `0`.

**Implement:** `def maxDepth(self, root: Optional[TreeNode]) -> int`

## Examples

**Example 1**

```text
Input:  root = [6, 2, null, 1, null, 0]
Output: 4
```

A left-leaning chain `6 -> 2 -> 1 -> 0`.

**Example 2**

```text
Input:  root = []
Output: 0
```

**Example 3**

```text
Input:  root = [4]
Output: 1
```

## Constraints

- The tree has between `0` and `10^4` nodes.
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

_Problem restated in my own words. See [LeetCode 104](https://leetcode.com/problems/maximum-depth-of-binary-tree/) for the official statement._
