# Next.js router.push() Error Handling
This repository demonstrates a common error encountered when using the `router.push()` method in Next.js: attempting to navigate to a route that doesn't exist.  The example shows how this can lead to unexpected crashes and how to implement proper error handling.

## Problem
The `bug.js` file contains a component that uses `router.push()` to navigate to a nonexistent route.  This will cause a runtime error if no appropriate error handling is implemented.

## Solution
The `bugSolution.js` file demonstrates how to mitigate this problem by checking if the route exists before attempting to navigate to it, providing a more robust user experience.  It also demonstrates how to use `router.replace()` for a more seamless user experience. 

This example provides a simple but important lesson in defensive programming for Next.js applications.