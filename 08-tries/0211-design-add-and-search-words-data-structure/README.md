# 211. Design Add and Search Words Data Structure

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Tries](../README.md) | [LeetCode 211](https://leetcode.com/problems/design-add-and-search-words-data-structure/) |

## Problem

Design a `WordDictionary` that supports adding words and searching with a single-character wildcard.

- `WordDictionary()` creates an empty structure.
- `void addWord(word)` stores `word`.
- `bool search(word)` returns `true` if some stored word matches `word`, where each `.` in the query matches any one letter. The match must cover the whole word (same length).

**Implement:** `class WordDictionary: addWord(self, word: str) -> None; search(self, word: str) -> bool`

## Examples

**Example 1**

```text
Input:  ops = ["WordDictionary", "addWord", "addWord", "addWord", "search", "search", "search", "search", "search"]
args = [[], ["map"], ["mop"], ["tape"], ["m.p"], ["..p"], ["t..e"], ["ma"], [".a.e"]]
Output: [null, null, null, null, true, true, true, false, true]
```

`ma` is only a prefix, so it does not match; `.a.e` matches `tape`.

**Example 2**

```text
Input:  ops = ["WordDictionary", "addWord", "search", "search"]
args = [[], ["a"], ["."], [".."]]
Output: [null, null, true, false]
```

Length must match exactly.

## Constraints

- `1 <= word.length <= 25`
- Words passed to `addWord` contain only lowercase letters.
- Search queries contain lowercase letters or `.`, with at most `2` dots per query.
- At most `10^4` calls to `addWord` and `search`.

## Notes

- Examples list the operation names and their arguments in parallel; the output shows each call's return value.

<details>
<summary>Hint (spoiler)</summary>

- A trie with DFS branching on `.` is the standard approach.

</details>

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 211](https://leetcode.com/problems/design-add-and-search-words-data-structure/) for the official statement._
