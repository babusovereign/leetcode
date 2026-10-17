# 155. Min Stack

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Stack](../README.md) | [LeetCode 155](https://leetcode.com/problems/min-stack/) |

## Problem

Design a stack that, in addition to the usual operations, can report its smallest element, with every operation running in O(1) time. Implement a `MinStack` class with: a constructor, `push(val)` to add an element, `pop()` to remove the top element, `top()` to return the top element, and `getMin()` to return the minimum element currently in the stack.

**Implement:** `class MinStack: push(val: int) -> None, pop() -> None, top() -> int, getMin() -> int`

## Examples

**Example 1**

```text
Input:  ops = ["MinStack", "push", "push", "push", "getMin", "pop", "top", "getMin", "push", "getMin"]
args = [[], [4], [2], [7], [], [], [], [], [-3], []]
Output: [null, null, null, null, 2, null, 2, 2, null, -3]
```

After popping `7`, the stack is `[4, 2]`; pushing `-3` makes it the new minimum.

**Example 2**

```text
Input:  ops = ["MinStack", "push", "push", "getMin", "pop", "getMin"]
args = [[], [5], [5], [], [], []]
Output: [null, null, null, 5, null, 5]
```

Duplicate minimums: after removing one `5`, the other remains the minimum.

## Constraints

- -2^31 <= val <= 2^31 - 1
- `pop`, `top`, and `getMin` are only called on a non-empty stack.
- At most 3 * 10^4 calls in total.

## Notes

- The example input lists each method call and its arguments; the output lists each call's return value (`null` for constructors and void methods).

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 155](https://leetcode.com/problems/min-stack/) for the official statement._
