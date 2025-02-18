# Unhandled Conditions in MATLAB Function

This repository demonstrates a common issue in MATLAB: unhandled conditions in a function that can lead to unexpected results or errors.  The function `myFunction` contains a conditional statement (`if-else`), but it may not cover all possible scenarios. This can result in incorrect calculations or function failures in edge cases. The solution demonstrates a more robust approach by explicitly handling additional scenarios.

## Bug
The `bug.m` file contains the problematic function `myFunction`. The function may return unexpected results or fail entirely if certain conditions are met.

## Solution
The `bugSolution.m` file presents an improved version of `myFunction` that addresses the unhandled conditions by adding more comprehensive error handling and logic.
