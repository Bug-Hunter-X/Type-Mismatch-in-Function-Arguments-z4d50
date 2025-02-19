# Type Mismatch in Function Arguments
This repository demonstrates a common TypeScript error: type mismatch in function arguments. The `add` function is defined to accept two numbers, but the code attempts to pass a string as the second argument. This results in a type error.

## Bug
The `bug.ts` file contains the buggy code.  The TypeScript compiler will correctly identify the type error.

## Solution
The `bugSolution.ts` file shows how to fix the issue by ensuring both arguments passed to the `add` function are of type `number`.