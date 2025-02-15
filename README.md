# MongoDB $inc Operator Error: Invalid Increment Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB to increment a field's value. The error arises from attempting to increment a field with a string value instead of a numerical value.  This example uses Javascript and the MongoDB Node.js driver. 

## Bug
The `bug.js` file shows the incorrect usage of `$inc`.  It attempts to increment the `field` with a string value 'value' which throws an error.

## Solution
The `bugSolution.js` file provides the correct solution. The `field` must be a number to be incremented using `$inc`.