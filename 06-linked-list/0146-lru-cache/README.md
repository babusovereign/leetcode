# 146. LRU Cache

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Linked List](../README.md) | [LeetCode 146](https://leetcode.com/problems/lru-cache/) |

## Problem

Design a class `LRUCache` that holds at most `capacity` key-value pairs and evicts the least recently used entry when full.

- `LRUCache(int capacity)` creates an empty cache.
- `int get(int key)` returns the value for `key`, or `-1` if absent. A successful `get` counts as a use.
- `void put(int key, int value)` inserts or updates `key`. Writing counts as a use. If an insert pushes the size past `capacity`, remove the least recently used key.

Both `get` and `put` must run in O(1) average time.

**Implement:** `class LRUCache: __init__(self, capacity: int); get(self, key: int) -> int; put(self, key: int, value: int) -> None`

## Examples

**Example 1**

```text
Input:  ops = ["LRUCache", "put", "put", "get", "put", "get", "put", "get", "put", "get", "get"]
args = [[2], [1, 10], [2, 20], [1], [3, 30], [2], [1, 15], [1], [4, 40], [3], [4]]
Output: [null, null, null, 10, null, -1, null, 15, null, -1, 40]
```

`get(1)` makes key 1 recent, so `put(3, 30)` evicts key 2. Updating key 1 makes it recent again, so `put(4, 40)` evicts key 3.

**Example 2**

```text
Input:  ops = ["LRUCache", "put", "get", "put", "get", "get"]
args = [[1], [7, 70], [7], [8, 80], [7], [8]]
Output: [null, null, 70, null, -1, 80]
```

With capacity 1, every new key evicts the previous one.

## Constraints

- `1 <= capacity <= 3000`
- `0 <= key <= 10^4`
- `0 <= value <= 10^5`
- At most `2 * 10^5` calls to `get` and `put`.

## Notes

- Examples list the operation names and their arguments in parallel; the output shows each call's return value (`null` for constructors and `put`).

<details>
<summary>Hint (spoiler)</summary>

- Standard approach: hash map plus doubly linked list.

</details>

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 146](https://leetcode.com/problems/lru-cache/) for the official statement._
