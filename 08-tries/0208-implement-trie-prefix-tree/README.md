# 208. Implement Trie (Prefix Tree)

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Tries](../README.md) | [LeetCode 208](https://leetcode.com/problems/implement-trie-prefix-tree/) |

## Problem

Implement a `Trie` (prefix tree) storing lowercase words.

- `Trie()` creates an empty trie.
- `void insert(String word)` adds `word`.
- `boolean search(String word)` returns `true` only if `word` itself was inserted.
- `boolean startsWith(String prefix)` returns `true` if any inserted word begins with `prefix`.

**Implement:** `class Trie: insert(self, word: str) -> None; search(self, word: str) -> bool; startsWith(self, prefix: str) -> bool`

## Examples

**Example 1**

```text
Input:  ops = ["Trie", "insert", "insert", "search", "search", "startsWith", "startsWith", "insert", "search"]
args = [[], ["card"], ["care"], ["car"], ["card"], ["car"], ["cat"], ["car"], ["car"]]
Output: [null, null, null, false, true, true, false, null, true]
```

`car` is only a prefix until it is inserted as a word itself; `cat` is not a prefix of any word.

## Constraints

- `1 <= word.length, prefix.length <= 2000`
- `word` and `prefix` contain only lowercase English letters.
- At most `3 * 10^4` total calls.

## Notes

- Examples list the operation names and their arguments in parallel; the output shows each call's return value (`null` for the constructor and `insert`).
- Each node needs an end-of-word flag to tell a stored word from a mere prefix.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 208](https://leetcode.com/problems/implement-trie-prefix-tree/) for the official statement._
