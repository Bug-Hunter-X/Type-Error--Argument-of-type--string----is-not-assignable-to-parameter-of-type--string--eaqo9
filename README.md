# TypeScript Type Error: Argument of type 'string[]' is not assignable to parameter of type 'string'

This repository demonstrates a common TypeScript error and its solution. The error occurs when trying to pass an array of strings to a function expecting a single string argument.

## Bug

The `bug.ts` file contains the erroneous code.  It defines a function `greeter` expecting a single string but then attempts to pass an array of strings to it.

## Solution

The `bugSolution.ts` file shows how to fix the error by correctly handling the array input, either by iterating over the array or by modifying the function signature.