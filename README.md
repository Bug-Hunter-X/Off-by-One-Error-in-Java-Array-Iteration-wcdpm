# Off-by-One Error in Java Array Iteration
This repository demonstrates a common off-by-one error in Java when iterating over an array.  The error occurs due to an incorrect loop condition which causes an `ArrayIndexOutOfBoundsException`. The solution shows how to correctly iterate.

## Bug
The `bug.java` file contains the buggy code.  The loop attempts to access an element beyond the array's bounds.

## Solution
The `bugSolution.java` file provides the corrected code with the proper loop condition to avoid the error.