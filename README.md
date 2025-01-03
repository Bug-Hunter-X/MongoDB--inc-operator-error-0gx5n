# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries.  The issue arises from attempting to increment a field by a non-numeric value.  The `$inc` operator expects a numeric value to increment the field by. Attempting to use a string will result in an error or unexpected behavior.

## Bug
The `bug.js` file shows the incorrect usage of the `$inc` operator where the increment value is a string '1' instead of a number 1. 

## Solution
The `bugSolution.js` file demonstrates the correct usage of the `$inc` operator which correctly increments the field by 1.
