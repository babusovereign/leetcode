# 355. Design Twitter

| Difficulty | Pattern | Link |
| --- | --- | --- |
| Medium | [Heap / Priority Queue](../README.md) | [LeetCode 355](https://leetcode.com/problems/design-twitter/) |

## Problem

Design a simplified social feed. Implement a `Twitter` class with: `postTweet(userId, tweetId)` to publish a new tweet (each `tweetId` is unique); `getNewsFeed(userId)` to return the IDs of up to 10 most recent tweets posted by that user or by anyone they follow, newest first; `follow(followerId, followeeId)`; and `unfollow(followerId, followeeId)`. Recency is the order in which `postTweet` calls happen. Users always see their own tweets, and following or unfollowing yourself has no effect.

**Implement:** `postTweet(int userId, int tweetId)`, `List<Integer> getNewsFeed(int userId)`, `follow(int followerId, int followeeId)`, `unfollow(int followerId, int followeeId)`

## Examples

**Example 1**

```text
Input:  ops = ["Twitter", "postTweet", "postTweet", "getNewsFeed", "follow", "postTweet", "getNewsFeed", "unfollow", "getNewsFeed"], args = [[], [7, 101], [3, 202], [7], [7, 3], [3, 303], [7], [7, 3], [7]]
Output: [null, null, null, [101], null, null, [303, 202, 101], null, [101]]
```

User 7 sees only their own tweet until following 3; after unfollowing, 3's tweets disappear from 7's feed.

**Example 2**

```text
Input:  ops = ["Twitter", "follow", "getNewsFeed", "postTweet" x11 (tweetIds 1..11 by user 1), "getNewsFeed"], args = [[], [1, 1], [1], [1, 1], [1, 2], ..., [1, 11], [1]]
Output: [null, null, [], null x11, [11, 10, 9, 8, 7, 6, 5, 4, 3, 2]]
```

Following yourself is a no-op, a feed with no tweets is empty, and the feed is capped at the 10 most recent tweets.

## Constraints

- All `tweetId` values are unique.
- Total number of calls is up to about 3 * 10^4.

## Notes

- What happens on unfollowing someone you don't follow? (Treat it as a no-op.)

## My solution

- [ ] Solved

Add solution files to this folder, for example `Solution.java` and `solution.py`.

**Approach:**

**Time:**  
**Space:**

---

_Problem restated in my own words. See [LeetCode 355](https://leetcode.com/problems/design-twitter/) for the official statement._
