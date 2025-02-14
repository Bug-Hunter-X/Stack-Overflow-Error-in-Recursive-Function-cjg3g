# Stack Overflow Bug in Recursive JavaScript Function

This repository demonstrates a common error in recursive JavaScript functions: stack overflow. The `myFunction` attempts to recursively subtract 1 from both inputs until one of them becomes 0.  However, if the inputs are large, the recursion depth exceeds the call stack limit, resulting in a stack overflow error.

The solution provides an iterative approach to avoid the recursion and prevent the stack overflow.

## How to reproduce the bug

1. Clone this repository.
2. Open `bug.js`.
3. Run the `myFunction` with relatively large numbers as arguments (e.g., `myFunction(10000, 10000)`).
4. Observe the stack overflow error in your console.