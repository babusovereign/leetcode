# 703. Kth Largest Element in a Stream

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Easy | [Heap / Priority Queue](../README.md) | [LeetCode 703](https://leetcode.com/problems/kth-largest-element-in-a-stream/) |

## Problem

Design a class `KthLargest` that tracks the `k`-th largest value in a stream of integers. The constructor receives `k` and an initial array `nums`. Each call to `add(val)` appends `val` to the stream and returns the `k`-th largest value among everything seen so far (counting duplicates, i.e. by position in sorted order, not the k-th distinct value).

**Implement:** `KthLargest(int k, int[] nums)`, `int add(int val)`

## Examples

**Example 1**

```text
Input:  ops = ["KthLargest", "add", "add", "add", "add"], args = [[2, [5, 1, 8]], [3], [9], [7], [10]]
Output: [null, 5, 8, 8, 9]
```

After adding 9 the stream is [5, 1, 8, 3, 9]; its 2nd largest is 8.

**Example 2**

```text
Input:  ops = ["KthLargest", "add", "add", "add"], args = [[1, []], [-4], [-7], [2]]
Output: [null, -4, -4, 2]
```

With k = 1 each call returns the running maximum; the initial array may be empty.

## Constraints

- `nums` may be empty initially, but whenever `add` is called the stream holds at least `k` values.
- Up to about 10^4 calls to `add`.

## Notes

- Is it k-th largest counting duplicates? (Yes.)

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 703](https://leetcode.com/problems/kth-largest-element-in-a-stream/) for the official statement._
