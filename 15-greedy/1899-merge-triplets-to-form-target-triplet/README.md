# 1899. Merge Triplets to Form Target Triplet

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Greedy](../README.md) | [LeetCode 1899](https://leetcode.com/problems/merge-triplets-to-form-target-triplet/) |

## Problem

You are given a list of triplets `triplets[i] = [a, b, c]` and a `target` triplet `[x, y, z]`. You may repeatedly pick two triplets `i` and `j` and overwrite `triplets[j]` with their element-wise maximum: `[max(a_i, a_j), max(b_i, b_j), max(c_i, c_j)]`.

Return `true` if, after any number of such operations (including zero), `target` appears as one of the triplets; otherwise return `false`.

**Implement:** `def mergeTriplets(self, triplets: list[list[int]], target: list[int]) -> bool`

## Examples

**Example 1**

```text
Input:  triplets = [[1, 4, 2], [3, 2, 5], [2, 4, 1]], target = [3, 4, 5]
Output: true
```

Merging `[1, 4, 2]` with `[3, 2, 5]` gives `[3, 4, 5]`.

**Example 2**

```text
Input:  triplets = [[2, 6, 3], [1, 2, 7]], target = [2, 2, 7]
Output: false
```

Only `[1, 2, 7]` stays within the target, and it cannot raise its first value to 2.

**Example 3**

```text
Input:  triplets = [[4, 1, 2], [1, 3, 5], [4, 3, 1]], target = [4, 3, 2]
Output: true
```

`[4, 1, 2]` merged with `[4, 3, 1]` gives `[4, 3, 2]`; `[1, 3, 5]` must be avoided because 5 overshoots.

## Constraints

- 1 <= triplets.length <= 10^5
- triplets[i].length == target.length == 3
- 1 <= a_i, b_i, c_i, x, y, z <= 1000

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 1899](https://leetcode.com/problems/merge-triplets-to-form-target-triplet/) for the official statement._
