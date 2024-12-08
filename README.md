# MongoDB $inc operator bug
This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries. The error occurs when providing a string value to the `$inc` operator instead of a number. This results in the update operation failing or producing unexpected results.

## Bug
The `bug.js` file contains the code that demonstrates the incorrect usage of the `$inc` operator.

## Solution
The `bugSolution.js` file contains the corrected code that addresses the issue by using a numeric value with the `$inc` operator.  This ensures the `counter` field is incremented correctly.