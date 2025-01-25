# Off-by-one Error in Java Array Iteration
This example demonstrates a common off-by-one error in Java when iterating over an array.  The loop condition `i <= arr.length` causes an `ArrayIndexOutOfBoundsException` because the valid indices are 0 to `arr.length - 1`. The solution shows how to correct the loop condition to avoid this error.

## How to reproduce the bug
1. Compile and run `bug.java`.
2. Observe the `ArrayIndexOutOfBoundsException`.