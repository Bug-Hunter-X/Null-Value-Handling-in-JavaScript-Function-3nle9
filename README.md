# Null Value Handling in JavaScript Function

This repository demonstrates a common error in JavaScript: improper handling of null values passed as function arguments.  The `bug.js` file showcases a function that fails to gracefully handle `null` inputs, while `bugSolution.js` provides the corrected implementation.

## Problem

When functions don't explicitly check for `null` or `undefined` values, they can throw errors or produce unexpected results.  This is especially problematic when interacting with external APIs or user inputs.

## Solution

The solution involves adding explicit checks at the beginning of the function to handle `null` values appropriately. This could involve returning a default value, throwing a more informative error, or performing alternative logic.