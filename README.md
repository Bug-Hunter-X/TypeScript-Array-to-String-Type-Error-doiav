# TypeScript Array to String Type Error

This example demonstrates a common TypeScript error that arises when passing an array to a function expecting a string argument.  The function `greeter` is designed to take a single string, but the `user` variable is an array of strings.  This leads to a type error.

The solution involves either modifying the function signature to accept an array or iterating through the array and calling the function for each element.