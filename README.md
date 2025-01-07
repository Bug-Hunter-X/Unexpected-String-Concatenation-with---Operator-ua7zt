# Unexpected String Concatenation in JavaScript
This example demonstrates how JavaScript's loose typing and the behavior of the `+` operator can lead to unexpected results when dealing with strings and numbers.  The `+` operator performs addition for numbers but concatenation for strings. This can cause subtle bugs that are difficult to track down.

## How to reproduce

1.  Clone the repository.
2.  Open `bug.js` and run it using a JavaScript runtime (e.g., Node.js).
3.  Observe the output.

## Solution

The solution involves explicit type checking or conversion to ensure consistent behavior.  See the `bugSolution.js` file for examples of how to handle this situation and get expected outputs.
