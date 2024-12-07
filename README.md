# Julia NaN Handling Bug
This repository demonstrates a common error in Julia: incorrect handling of NaN (Not a Number) values. The `my_function` does not explicitly check for NaN, leading to unexpected behavior when NaN is passed as input.  The solution involves adding a check for `isnan()` to handle NaN gracefully.

## Bug
The original `my_function` lacks a check for NaN, which can lead to unexpected results or errors when working with floating-point numbers.

## Solution
The solution includes an explicit check for NaN using `isnan()`, providing a more robust and predictable function.
