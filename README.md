# 3Sum

## Problem Statement
Given an array of **nums** of **n** integers, are there elements *a*, *b*, *c* in **nums** such that *a + b + c = 0*? Find all unique triplets in the array which gives the sum of zero.

### Note
The solution set must not contain duplicate triplets.

### Example
Given array **nums** = [-1, 0, 1, 2, -1, -4],

A solution set is:

[
  [-1, 0, 1],
  [-1, -1, 2]
]

## Solution Approach 1 - Brute Force
Consider all possible triplets using 3 nested loops, and if the sum of the triplet equals 0, add it to a set of vector (after sorting those 3 numbers). This will make sure that the final result doesn't contain any duplicate triplets.

### Time Complexity
This solution takes a time complexity of O(N^3 log N).