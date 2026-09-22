# Diagonal Difference

## Problem
Given a square matrix, calculate the absolute difference between the sums of its primary diagonal and secondary diagonal.

## Approach
- Traverse the matrix once.
- Add `arr[i][i]` to the primary diagonal sum.
- Add `arr[i][n - 1 - i]` to the secondary diagonal sum.
- Return the absolute difference between the two sums.

## Time Complexity
**O(N)**

## Space Complexity
**O(1)**

## HackerRank
Problem: [Diagonal Difference](https://www.hackerrank.com/challenges/diagonal-difference/problem)

The solution was submitted and tested on HackerRank.