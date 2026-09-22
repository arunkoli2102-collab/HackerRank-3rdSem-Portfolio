# Compare the Triplets

## Problem Description

Alice and Bob each have a set of three scores. The scores are compared one by one.

- If Alice's score is greater, Alice receives 1 point.
- If Bob's score is greater, Bob receives 1 point.
- If both scores are equal, neither receives a point.

The final result contains Alice's score followed by Bob's score.

## Approach

1. Compare the three scores one by one.
2. If Alice's score is greater, increase Alice's count.
3. If Bob's score is greater, increase Bob's count.
4. Ignore equal scores.
5. Return the two scores as a vector.

## Example

Input:

```text
5 6 7
3 6 10
```

Output:

```text
1 1
```

## Key Concept

The solution uses:
- Vectors
- `for` loop
- Conditional statements
- Simple comparison

## Time Complexity

**O(1)**

Since there are exactly three scores to compare.

## Space Complexity

**O(1)**

Only a constant amount of extra space is used.

## HackerRank

Problem: [Compare the Triplets](https://www.hackerrank.com/challenges/compare-the-triplets/problem)

Platform: HackerRank

The solution was submitted and tested on HackerRank.