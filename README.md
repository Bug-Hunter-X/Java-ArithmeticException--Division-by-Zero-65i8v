# Java ArithmeticException: Division by Zero

This repository demonstrates a common Java error: the `ArithmeticException` that occurs when dividing by zero.  The `Bug.java` file contains the erroneous code, while `BugSolution.java` provides the corrected version.

The bug is caused by a lack of input validation. The program doesn't check if the divisor (`y`) is zero before performing the division. This can lead to unexpected crashes and program termination.

The solution introduces a simple check to avoid division by zero.  This is a crucial best practice for preventing runtime errors in any programming language.