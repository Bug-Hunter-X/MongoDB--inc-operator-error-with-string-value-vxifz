# MongoDB $inc Operator Error with String Value

This repository demonstrates an uncommon error that can occur when using the `$inc` operator in MongoDB update operations. The error arises from providing a string value instead of a numeric value to the `$inc` operator, leading to unexpected behavior or errors.

## Bug Description
The provided code snippet attempts to increment the `count` field of a document by 10. However, instead of providing a numerical value, it uses a string "10". This results in incorrect behavior.  The `$inc` operator expects a numeric value and will throw an error or produce unexpected results when a string is used. 

## Solution
The solution involves ensuring that the value provided to the `$inc` operator is a number, not a string. 