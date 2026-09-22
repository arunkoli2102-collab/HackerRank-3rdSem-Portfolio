# Dynamic Array

## Problem Description

The Dynamic Array problem requires processing a set of queries using multiple dynamic sequences. Each query uses the XOR operation with `lastAnswer` to determine which sequence should be accessed.

## Approach

1. Create `n` empty sequences.
2. For a type `1` query, calculate the sequence index using:
   `index = (x ^ lastAnswer) % n`
3. Append `y` to the selected sequence.
4. For a type `2` query, calculate the sequence index using the same formula.
5. Select the required element using:
   `y % sequence.size()`.
6. Update `lastAnswer` and store the result.

## Key Concept

The problem uses:
- Dynamic arrays (vectors)
- Nested sequences
- Bitwise XOR (`^`)
-