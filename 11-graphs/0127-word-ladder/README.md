# 127. Word Ladder

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Hard | [Graphs](../README.md) | [LeetCode 127](https://leetcode.com/problems/word-ladder/) |

## Problem

Given `beginWord`, `endWord`, and a dictionary `wordList`, find the length of the shortest transformation sequence from `beginWord` to `endWord`, where each step changes exactly one letter and every intermediate word (and `endWord`) must be in `wordList`. The length counts the words in the sequence, including both ends. Return `0` if no such sequence exists.

**Implement:** `int ladderLength(String beginWord, String endWord, List<String> wordList)`

## Examples

**Example 1**

```text
Input:  beginWord = "cold", endWord = "warm", wordList = ["cord", "card", "ward", "warm", "word", "worm", "wore", "core"]
Output: 5
```

One shortest sequence: cold -> cord -> word -> worm -> warm (5 words).

**Example 2**

```text
Input:  beginWord = "lead", endWord = "gold", wordList = ["load", "goad", "gold", "lend"]
Output: 4
```

lead -> load -> goad -> gold.

**Example 3**

```text
Input:  beginWord = "cat", endWord = "dog", wordList = ["cot", "cog", "dot"]
Output: 0
```

"dog" is not in the word list, so no sequence exists.

## Constraints

- 1 <= beginWord.length <= 10
- All words have the same length and contain only lowercase English letters.
- 1 <= wordList.length <= 5000
- `beginWord != endWord`; words in `wordList` are unique.
- `beginWord` need not be in `wordList`.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 127](https://leetcode.com/problems/word-ladder/) for the official statement._
