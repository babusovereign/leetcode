# 105. Construct Binary Tree from Preorder and Inorder Traversal

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Trees](../README.md) | [LeetCode 105](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) |

## Problem

You are given two integer arrays, `preorder` and `inorder`, holding the pre-order and in-order traversals of the same binary tree. All values are unique. Rebuild the tree and return its root.

**Implement:** `def buildTree(self, preorder: list[int], inorder: list[int]) -> Optional[TreeNode]`

## Examples

**Example 1**

```text
Input:  preorder = [4, 2, 1, 3, 7, 9], inorder = [1, 2, 3, 4, 7, 9]
Output: [4, 2, 7, 1, 3, null, 9]
```

**Example 2**

```text
Input:  preorder = [1], inorder = [1]
Output: [1]
```

**Example 3**

```text
Input:  preorder = [1, 2, 3], inorder = [3, 2, 1]
Output: [1, 2, null, 3]
```

The tree is a chain of left children: `1 -> 2 -> 3`.

## Constraints

- `1 <= preorder.length <= 3000`
- `inorder.length == preorder.length`
- `-3000 <= values <= 3000`
- All values are unique, and both arrays describe the same tree.

## Notes

- The output is shown in level-order notation with `null` for missing children.
- Precompute a value-to-index map of `inorder` to get O(n) instead of O(n^2).

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 105](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) for the official statement._
