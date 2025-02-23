# MongoDB $inc Operator Error
This repository demonstrates a common error when using the `$inc` operator in MongoDB updates. The error arises from attempting to increment a field using a string value instead of a numeric value.

## Bug Description
The provided JavaScript code uses `$inc` with a string value ('1') which causes an error.  The `$inc` operator requires a numerical value to correctly increment the specified field.

## Solution
The solution is to supply a numeric value (1) to the `$inc` operator to correctly increment the field.
