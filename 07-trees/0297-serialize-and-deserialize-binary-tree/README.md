# 297. Serialize and Deserialize Binary Tree

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Hard | [Trees](../README.md) | [LeetCode 297](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/) |

## Problem

Design a `Codec` class that converts a binary tree to a string and back. `serialize(root)` returns a string encoding of the tree, and `deserialize(data)` must rebuild exactly the same tree (same shape and values) from that string.

The string format is entirely up to you; the only requirement is that `deserialize(serialize(root))` reproduces the original tree.

**Implement:** `class Codec: serialize(self, root: Optional[TreeNode]) -> str; deserialize(self, data: str) -> Optional[TreeNode]`

## Examples

**Example 1**

```text
Input:  root = [1, 2, 3, null, null, 4, 5]
Output: [1, 2, 3, null, null, 4, 5]
```

The serialized string can be any format, as long as decoding restores this exact tree.

**Example 2**

```text
Input:  root = []
Output: []
```

**Example 3**

```text
Input:  root = [-8, null, 12, 0]
Output: [-8, null, 12, 0]
```

Negative values and `0` must round-trip correctly.

## Constraints

- The tree has between `0` and `10^4` nodes.
- `-1000 <= Node.val <= 1000`

## Notes

- Trees are written in level-order with `null` for missing children (e.g. `root = [3, 1, 4, null, 2]`); `[]` is an empty tree. Each example shows the tree returned by `deserialize(serialize(root))`.
- Values can be negative or multi-digit, so the encoding needs delimiters and an explicit marker for missing children.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 297](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/) for the official statement._
