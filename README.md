# Ada Constraint_Error: Division by Zero

This repository demonstrates a common runtime error in Ada: the `Constraint_Error` exception arising from division by zero.  The `bug.ada` file contains the erroneous code, while `bugSolution.ada` provides a corrected version with proper exception handling.

The original code attempts to divide an integer by zero, leading to a runtime crash. The solution shows how to use an `exception` block to gracefully handle this situation, preventing program termination and providing informative error messages.