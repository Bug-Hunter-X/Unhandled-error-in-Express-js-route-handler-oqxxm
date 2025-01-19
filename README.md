# Unhandled Error in Express.js Route Handler

This repository demonstrates a common error in Express.js route handlers: the lack of error handling for invalid input.

The `bug.js` file contains a route handler that retrieves a user by ID. However, it does not handle the case where the user ID is not a valid number. This leads to unexpected errors and potential crashes.

The `bugSolution.js` file provides a solution that addresses this issue by adding proper error handling.