# Javascript Implicit Type Coercion Bug
This repo demonstrates a common Javascript bug caused by implicit type coercion. The `foo` function intends to add two numbers, but due to implicit type conversion, it performs string concatenation when one of the inputs is a string.

## Bug
The `bug.js` file contains the buggy code.  The function `foo` should add `a` and `b`, but when `b` is a string, it concatenates them instead of adding numerically.

## Solution
The `bugSolution.js` file shows a corrected version. Explicit type checking and conversion ensures correct numerical addition.