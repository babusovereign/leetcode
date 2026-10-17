# 207. Course Schedule

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Graphs](../README.md) | [LeetCode 207](https://leetcode.com/problems/course-schedule/) |

## Problem

There are `numCourses` courses labelled `0` to `numCourses - 1`. Each pair `[a, b]` in `prerequisites` means course `b` must be completed before course `a`. Return `true` if it is possible to finish every course, i.e. the prerequisite graph has no cycle, and `false` otherwise.

**Implement:** `boolean canFinish(int numCourses, int[][] prerequisites)`

## Examples

**Example 1**

```text
Input:  numCourses = 3, prerequisites = [[1, 0], [2, 1]]
Output: true
```

Take 0, then 1, then 2.

**Example 2**

```text
Input:  numCourses = 3, prerequisites = [[0, 1], [1, 2], [2, 0]]
Output: false
```

0 needs 1, 1 needs 2, 2 needs 0: a cycle.

**Example 3**

```text
Input:  numCourses = 4, prerequisites = []
Output: true
```

No prerequisites at all.

## Constraints

- 1 <= numCourses <= 2000
- 0 <= prerequisites.length <= 5000
- All prerequisite pairs are distinct.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 207](https://leetcode.com/problems/course-schedule/) for the official statement._
