# 295. Find Median from Data Stream

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Hard | [Heap / Priority Queue](../README.md) | [LeetCode 295](https://leetcode.com/problems/find-median-from-data-stream/) |

## Problem

Design a `MedianFinder` that receives integers one at a time and can report the median of all values seen so far. `addNum(num)` inserts a value and `findMedian()` returns the median as a floating-point number: the middle value when the count is odd, or the average of the two middle values when it is even. Both operations should be fast, as they may be interleaved many times.

**Implement:** `void addNum(int num)`, `double findMedian()`

## Examples

**Example 1**

```text
Input:  ops = ["MedianFinder", "addNum", "findMedian", "addNum", "findMedian", "addNum", "findMedian", "addNum", "findMedian"], args = [[], [5], [], [-2], [], [10], [], [3], []]
Output: [null, null, 5.0, null, 1.5, null, 5.0, null, 4.0]
```

Sorted values after the last insert are [-2, 3, 5, 10], so the median is (3 + 5) / 2 = 4.0.

**Example 2**

```text
Input:  ops = ["MedianFinder", "addNum", "addNum", "findMedian"], args = [[], [1], [2], []]
Output: [null, null, null, 1.5]
```

An even count can produce a non-integer median.

## Constraints

- `findMedian` is only called after at least one `addNum`.
- Up to about 5 * 10^4 total calls.
- Values fit in a 32-bit signed integer.

## Notes

- Follow-up: how would you optimise if all values were in a small range such as 0 to 100?

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 295](https://leetcode.com/problems/find-median-from-data-stream/) for the official statement._
