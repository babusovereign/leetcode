# 621. Task Scheduler

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Heap / Priority Queue](../README.md) | [LeetCode 621](https://leetcode.com/problems/task-scheduler/) |

## Problem

You are given a list of CPU tasks, each labelled with an uppercase letter, and a non-negative integer `n`. Each time unit the CPU either runs one task or sits idle. Two runs of the *same* label must be separated by at least `n` time units; tasks may be executed in any order. Return the minimum total number of time units needed to finish every task.

**Implement:** `int leastInterval(char[] tasks, int n)`

## Examples

**Example 1**

```text
Input:  tasks = ["A", "A", "A", "B", "B", "C"], n = 2
Output: 7
```

One optimal schedule: A B C A B idle A.

**Example 2**

```text
Input:  tasks = ["A", "B", "C", "D", "A", "B"], n = 1
Output: 6
```

No idle slots are needed, so the answer is just the number of tasks.

**Example 3**

```text
Input:  tasks = ["X", "X", "X", "X"], n = 3
Output: 13
```

Only one task type: X idle idle idle X idle idle idle X idle idle idle X.

## Constraints

- 1 <= tasks.length <= 10^4
- Task labels are uppercase English letters `A`-`Z`.
- 0 <= n <= 100

## Notes

- Only the count of the most frequent label(s) really determines the idle time.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 621](https://leetcode.com/problems/task-scheduler/) for the official statement._
