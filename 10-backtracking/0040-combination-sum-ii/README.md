# 40. Combination Sum II

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Backtracking](../README.md) | [LeetCode 40](https://leetcode.com/problems/combination-sum-ii/) |

## Problem

Given an array `candidates` (which may contain duplicate values) and a `target`, return all unique combinations whose elements sum to `target`, where each array element may be used at most once. The output must not contain duplicate combinations, even when the input has repeated values; order within and across combinations doesn't matter.

**Implement:** `List<List<Integer>> combinationSum2(int[] candidates, int target)`

## Examples

**Example 1**

```text
Input:  candidates = [2, 5, 2, 1, 2], target = 5
Output: [[1, 2, 2], [5]] (any order)
```

Each array element is used at most once, and duplicate values must not create duplicate combinations.

**Example 2**

```text
Input:  candidates = [1, 1, 1], target = 2
Output: [[1, 1]]
```

**Example 3**

```text
Input:  candidates = [3, 9], target = 4
Output: []
```

## Constraints

- 1 <= candidates.length <= 100
- 1 <= candidates[i] <= 50
- 1 <= target <= 30

<details>
<summary>Hint (spoiler)</summary>

- Sorting first makes it easy to skip duplicate values at the same recursion depth.

</details>

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 40](https://leetcode.com/problems/combination-sum-ii/) for the official statement._
