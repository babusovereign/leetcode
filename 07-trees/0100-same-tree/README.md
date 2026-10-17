# 100. Same Tree

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Easy | [Trees](../README.md) | [LeetCode 100](https://leetcode.com/problems/same-tree/) |

## Problem

Given the roots `p` and `q` of two binary trees, return `true` if they are identical — same shape and the same value at every corresponding node — and `false` otherwise.

**Implement:** `def isSameTree(self, p: Optional[TreeNode], q: Optional[TreeNode]) -> bool`

## Examples

**Example 1**

```text
Input:  p = [2, 1, 3], q = [2, 1, 3]
Output: true
```

**Example 2**

```text
Input:  p = [5, 4], q = [5, null, 4]
Output: false
```

Same values, but `4` is a left child in one tree and a right child in the other.

**Example 3**

```text
Input:  p = [], q = []
Output: true
```

Two empty trees are the same.

## Constraints

- Each tree has between `0` and `100` nodes.
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

_Problem restated in my own words. See [LeetCode 100](https://leetcode.com/problems/same-tree/) for the official statement._
