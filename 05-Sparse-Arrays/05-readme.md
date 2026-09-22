# Sparse Arrays

## Problem Description

Given a list of strings and a list of query strings, find how many times each query string occurs in the original list.

For every query, return its frequency in the string list.

## Approach

1. Create a frequency map using `unordered_map`.
2. Traverse the given string list.
3. Store the frequency of each string in the map.
4. Traverse the queries.
5. For each query, look up its frequency in the map.
6. Store the results and return them.

## Example

Input:

```text
4
aba
baba
aba
xzxb
3
aba
xzxb
ab
```

Output:

```text
2
1
0
```

## Key Concept

The solution uses:
- Strings
- Vectors
- `unordered_map`
- Frequency counting
- Hash map lookup

## Time Complexity

**O(N + Q)**

Where:
- `N` is the number of strings.
- `Q` is the number of queries.

## Space Complexity

**O(N)**

The frequency map stores the strings and their counts.

## HackerRank

Problem: [Sparse Arrays](https://www.hackerrank.com/challenges/sparse-arrays/problem)

Platform: HackerRank

The solution was submitted and tested on HackerRank.