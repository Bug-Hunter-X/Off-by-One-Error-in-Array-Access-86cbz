# Off-by-One Error in Java Array Access

This repository demonstrates a common off-by-one error in Java when accessing array elements. The `bug.java` file contains the erroneous code, while `bugSolution.java` provides the corrected version.

The error occurs because the loop condition `i <= array.length` attempts to access an element beyond the array's bounds.  Arrays in Java are zero-indexed, meaning the valid indices range from 0 to `array.length - 1`.

This example highlights the importance of careful loop condition checks when working with arrays and other data structures in Java to prevent runtime exceptions.