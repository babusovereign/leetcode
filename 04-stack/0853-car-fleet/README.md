# 853. Car Fleet

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Stack](../README.md) | [LeetCode 853](https://leetcode.com/problems/car-fleet/) |

## Problem

`n` cars drive toward a destination at mile `target` on a single-lane road. Car `i` starts at mile `position[i]` (all distinct) and drives at `speed[i]` miles per hour. A car can never pass the car ahead; when it catches up, it slows down and the two travel together at the slower speed as a single fleet. A car that catches another exactly at the destination still joins that fleet. Return how many separate fleets reach the destination.

**Implement:** `def carFleet(self, target: int, position: list[int], speed: list[int]) -> int`

## Examples

**Example 1**

```text
Input:  target = 12, position = [10, 8, 0, 5, 3], speed = [2, 4, 1, 1, 3]
Output: 3
```

The cars at 10 and 8 both arrive at time 1 and form one fleet. The car at 3 catches the car at 5 (arrival times 3 and 7) and they finish together. The car at 0 arrives alone at time 12.

**Example 2**

```text
Input:  target = 20, position = [4], speed = [3]
Output: 1
```

**Example 3**

```text
Input:  target = 10, position = [0, 2, 4], speed = [4, 2, 1]
Output: 1
```

The two rear cars both catch the slow front car before mile 10.

## Constraints

- n == position.length == speed.length
- 1 <= n <= 10^5
- 0 < target <= 10^6
- 0 <= position[i] < target
- All `position` values are distinct.
- 0 < speed[i] <= 10^6

## Notes

- A single car on its own also counts as a fleet.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 853](https://leetcode.com/problems/car-fleet/) for the official statement._
