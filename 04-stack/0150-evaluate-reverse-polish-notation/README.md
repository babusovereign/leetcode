# 150. Evaluate Reverse Polish Notation

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Stack](../README.md) | [LeetCode 150](https://leetcode.com/problems/evaluate-reverse-polish-notation/) |

## Problem

You are given an array of string `tokens` representing an arithmetic expression in Reverse Polish (postfix) notation, where each operator follows its two operands. Operators are `+`, `-`, `*`, and `/`; operands are integers. Evaluate the expression and return its integer value. Division between integers truncates toward zero, and the expression is always valid with no division by zero.

**Implement:** `def evalRPN(self, tokens: list[str]) -> int`

## Examples

**Example 1**

```text
Input:  tokens = ["3", "5", "+", "2", "*"]
Output: 16
```

`(3 + 5) * 2`.

**Example 2**

```text
Input:  tokens = ["7", "-2", "/", "4", "-"]
Output: -7
```

`7 / -2` truncates toward zero to `-3`, then `-3 - 4 = -7`.

**Example 3**

```text
Input:  tokens = ["42"]
Output: 42
```

## Constraints

- 1 <= tokens.length <= 10^4
- Each token is an operator or an integer in [-200, 200].
- The expression is valid and every intermediate result fits in a 32-bit integer.

## Notes

- Watch out for languages (like Python) whose `//` operator floors instead of truncating.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 150](https://leetcode.com/problems/evaluate-reverse-polish-notation/) for the official statement._
