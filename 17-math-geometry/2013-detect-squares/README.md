# 2013. Detect Squares

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Math & Geometry](../README.md) | [LeetCode 2013](https://leetcode.com/problems/detect-squares/) |

## Problem

Design a `DetectSquares` class that stores points on a 2D grid and answers counting queries. `add(point)` stores a point `[x, y]`; duplicate points are allowed and each copy is counted separately. `count(point)` takes a query point (which is not stored) and returns how many ways you can choose three stored points that, together with the query point, form the four corners of a square with positive area whose sides are parallel to the x- and y-axes.

**Implement:** `class DetectSquares: __init__(), add(point: list[int]) -> None, count(point: list[int]) -> int`

## Examples

**Example 1**

```text
Input:  operations = ["DetectSquares", "add", "add", "add", "count", "add", "count", "count"]
arguments = [[], [[1, 1]], [[1, 4]], [[4, 1]], [[4, 4]], [[1, 1]], [[4, 4]], [[2, 2]]]
Output: [null, null, null, null, 1, null, 2, 0]
```

The first count finds one square with side 3. After a second `[1, 1]` is added, the same square can be formed with either copy, giving 2. No square has `[2, 2]` as a corner.

**Example 2**

```text
Input:  operations = ["DetectSquares", "add", "add", "add", "add", "count"]
arguments = [[], [[0, 0]], [[0, 2]], [[2, 0]], [[0, 5]], [[2, 2]]]
Output: [null, null, null, null, null, 1]
```

The square `[0,0],[0,2],[2,0],[2,2]` is found; `[0, 5]` does not help.

## Constraints

- point.length == 2
- 0 <= x, y <= 1000
- At most 3000 calls in total to add and count.

## Notes

- Squares must be axis-aligned; rotated squares do not count.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 2013](https://leetcode.com/problems/detect-squares/) for the official statement._
