# 1448. Count Good Nodes in Binary Tree

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Trees](../README.md) | [LeetCode 1448](https://leetcode.com/problems/count-good-nodes-in-binary-tree/) |

## Problem

Given the `root` of a binary tree, a node `X` is called good if no node on the path from the root to `X` has a value strictly greater than `X`'s value. Return the number of good nodes. The root is always good.

**Implement:** `def goodNodes(self, root: TreeNode) -> int`

## Examples

**Example 1**

```text
Input:  root = [5, 2, 8, 6, null, 4, 9]
Output: 4
```

Good nodes: `5`, `6` (path `5, 2, 6`), `8`, `9`. Not good: `2` and `4`.

**Example 2**

```text
Input:  root = [-1]
Output: 1
```

**Example 3**

```text
Input:  root = [2, 2, 2]
Output: 3
```

Ties count as good.

## Constraints

- The tree has between `1` and `10^5` nodes.
- `-10^4 <= Node.val <= 10^4`

## Notes

- Trees are written in level-order with `null` for missing children (e.g. `root = [3, 1, 4, null, 2]`); `[]` is an empty tree.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 1448](https://leetcode.com/problems/count-good-nodes-in-binary-tree/) for the official statement._
