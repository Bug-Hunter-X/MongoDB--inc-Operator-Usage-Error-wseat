# MongoDB $inc Operator Usage Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment or decrement a numerical field in a document.  However, attempting to increment with a non-numerical value leads to unexpected results or errors.

## Bug Description
The provided code snippet shows incorrect usage of the `$inc` operator where a string value ("10") is passed instead of a number (10). This leads to the update operation failing or producing unexpected results.

## Solution
The solution involves ensuring that only numerical values are passed as arguments to the `$inc` operator.