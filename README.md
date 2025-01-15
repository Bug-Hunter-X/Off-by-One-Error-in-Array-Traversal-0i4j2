# Off-by-One Error in Java Array

This repository demonstrates a common off-by-one error in Java when iterating over an array.  The `bug.java` file contains the erroneous code, while `bugSolution.java` provides the corrected version.

The error occurs due to an incorrect loop condition which attempts to access an index beyond the bounds of the array.  This leads to an `ArrayIndexOutOfBoundsException` at runtime.

The solution corrects the loop condition to ensure that all iterations remain within the valid array index range.
