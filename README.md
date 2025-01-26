# JavaScript Null and Undefined Handling Error

This repository demonstrates a common error in JavaScript related to handling `null` and `undefined` values using loose equality.  The `bug.js` file contains code that incorrectly handles `undefined`, leading to a `TypeError`.  The corrected version is in `bugSolution.js`.

The issue arises from using `===` for strict equality instead of loose equality (`==`).  Strict equality differentiates between `null` and `undefined`, while loose equality treats them as equivalent in certain scenarios, leading to potential inconsistencies.