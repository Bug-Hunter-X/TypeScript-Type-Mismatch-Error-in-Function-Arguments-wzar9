# TypeScript Type Mismatch Error

This repository demonstrates a common TypeScript error: type mismatch in function arguments.  The `add` function is defined to accept two numbers, but the code attempts to pass a string as an argument. This leads to a type error during compilation.

## How to reproduce

1. Clone the repository.
2. Compile the code using the TypeScript compiler (tsc bug.ts).
3. Observe the compilation error.

## Solution

The solution involves ensuring that the arguments passed to the function match the types defined in the function signature.  The solution file (`bugSolution.ts`) demonstrates this correction.
