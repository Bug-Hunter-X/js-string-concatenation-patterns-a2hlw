# Unexpected String Concatenation in JavaScript

This repository demonstrates a common, yet easily overlooked, error in JavaScript: the unexpected concatenation of strings when performing addition with loosely typed variables.  The `bug.js` file shows the faulty code, while `bugSolution.js` provides the corrected version.

The issue stems from JavaScript's dynamic typing; it implicitly converts the number `1` to a string before concatenating it with the string `'2'`, resulting in `'12'` instead of the expected numerical sum `3`.

The solution involves explicitly checking the types of variables before performing addition, ensuring that they are both numbers, thus avoiding unexpected behavior.