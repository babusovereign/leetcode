# 210. Course Schedule II

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Graphs](../README.md) | [LeetCode 210](https://leetcode.com/problems/course-schedule-ii/) |

## Problem

Same setup as Course Schedule: `numCourses` courses labelled `0` to `numCourses - 1`, and each pair `[a, b]` in `prerequisites` means `b` must be taken before `a`. Return any ordering of all the courses that respects every prerequisite. If no valid ordering exists because of a cycle, return an empty array.

**Implement:** `int[] findOrder(int numCourses, int[][] prerequisites)`

## Examples

**Example 1**

```text
Input:  numCourses = 4, prerequisites = [[1, 0], [2, 0], [3, 1], [3, 2]]
Output: [0, 1, 2, 3] or [0, 2, 1, 3]
```

Course 0 comes first and course 3 last; 1 and 2 may be in either order. Any valid order is accepted.

**Example 2**

```text
Input:  numCourses = 2, prerequisites = [[0, 1], [1, 0]]
Output: []
```

The two courses depend on each other, so no order exists.

**Example 3**

```text
Input:  numCourses = 1, prerequisites = []
Output: [0]
```

## Constraints

- 1 <= numCourses <= 2000
- 0 <= prerequisites.length <= numCourses * (numCourses - 1)
- All prerequisite pairs are distinct; `a != b`.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 210](https://leetcode.com/problems/course-schedule-ii/) for the official statement._
