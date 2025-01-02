# Unexpected Null Handling in Addition Function

This repository demonstrates a common error in JavaScript related to unexpected null handling in an addition function.

The function `foo` is designed to add two numbers. However, it does not handle null values gracefully and returns null when either input is null.  A more robust solution would treat null values as 0 to prevent unexpected results.

## Bug
The `bug.js` file contains the erroneous code.

## Solution
The `bugSolution.js` file provides a corrected version of the function that handles null values correctly by treating them as 0.