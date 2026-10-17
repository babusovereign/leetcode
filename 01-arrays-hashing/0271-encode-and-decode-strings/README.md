# 271. Encode and Decode Strings

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Arrays & Hashing](../README.md) | [LeetCode 271](https://leetcode.com/problems/encode-and-decode-strings/) (Premium) |

> LeetCode Premium. The same problem is free to practise on [NeetCode](https://neetcode.io/practice).

## Problem

Design a scheme to serialize a list of strings into one string and to restore the original list from that string. Implement `encode`, which turns a list of strings into a single string, and `decode`, which inverts it so that `decode(encode(strs)) == strs` for every possible input.

The strings may contain any characters, including whatever delimiter you might be tempted to use, so the format must be unambiguous. Do not rely on language-level serialization helpers (such as `eval` or a JSON library).

**Implement:** `def encode(self, strs: list[str]) -> str / def decode(self, s: str) -> list[str]`

## Examples

**Example 1**

```text
Input:  strs = ["hi", "#there", "4#x"]
Output: ["hi", "#there", "4#x"]
```

The encoded form is up to you; only the round trip is checked. A length-prefixed format such as `"2#hi6##there3#4#x"` handles the embedded `#` characters.

**Example 2**

```text
Input:  strs = ["", ""]
Output: ["", ""]
```

Empty strings must survive the round trip and stay distinct from an empty list.

**Example 3**

```text
Input:  strs = []
Output: []
```

## Constraints

- 0 <= strs.length <= 200
- 0 <= strs[i].length <= 200
- `strs[i]` may contain any of the 256 ASCII characters.

## Notes

- The output shown is the result of `decode(encode(strs))`; the intermediate encoded string is not graded.

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 271](https://leetcode.com/problems/encode-and-decode-strings/) for the official statement._
