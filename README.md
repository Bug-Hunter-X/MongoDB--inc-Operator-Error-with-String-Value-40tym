# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB. The `$inc` operator is used to increment a numerical field by a specified value. However, if a string value is provided, an error will occur.

## Bug

The bug is in the `bug.js` file and it involves providing a string to the `$inc` operator, which leads to an error. 

## Solution

The solution is shown in `bugSolution.js`.  This corrects the use of the `$inc` operator by providing a numerical value.