# JavaScript NaN comparison
This repository demonstrates the unusual behavior of NaN in JavaScript's equality comparisons.  NaN (Not a Number) is a special numeric value that represents an undefined or unrepresentable numeric value.  The key issue is that NaN is never equal to itself, not even using strict equality (===).

## The Problem
The provided JavaScript code shows a function intended to compare two values for equality.  However, when both inputs are NaN, the function incorrectly returns false.

## The Solution
The provided solution demonstrates the correct way to check for NaN using the Number.isNaN() method. This method is more reliable and avoids the pitfalls associated with directly comparing NaN using equality operators.