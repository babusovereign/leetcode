# 572. Subtree of Another Tree

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Easy | [Trees](../README.md) | [LeetCode 572](https://leetcode.com/problems/subtree-of-another-tree/) |

## Problem

Given the roots of two binary trees, `root` and `subRoot`, return `true` if some node of `root` is the top of a subtree identical to `subRoot` (same structure and values, including everything below it down to the leaves). Otherwise return `false`. A tree counts as a subtree of itself.

**Implement:** `def isSubtree(self, root: Optional[TreeNode], subRoot: Optional[TreeNode]) -> bool`

## Examples

**Example 1**

```text
Input:  root = [7, 3, 9, 1, 4], subRoot = [3, 1, 4]
Output: true
```

**Example 2**

```text
Input:  root = [7, 3, 9, 1, 4, null, null, null, null, 2], subRoot = [3, 1, 4]
Output: false
```

The node `3` matches at the top, but in `root` its child `4` has an extra child `2`, so the subtrees are not identical.

**Example 3**

```text
Input:  root = [1, 1], subRoot = [1]
Output: true
```

The leaf `1` matches.

## Constraints

- `root` has between `1` and `2000` nodes.
- `subRoot` has between `1` and `1000` nodes.
- `-10^4 <= Node.val <= 10^4`

## Notes

- Trees are written in level-order with `null` for missing children (e.g. `root = [3, 1, 4, null, 2]`); `[]` is an empty tree.
- Matching must include the whole subtree to the leaves, not just a matching top portion.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 572](https://leetcode.com/problems/subtree-of-another-tree/) for the official statement._
