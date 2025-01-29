# Express.js Route Handler Missing Error Handling for Invalid User ID

This repository demonstrates a common error in Express.js route handlers: the lack of error handling for invalid input.  Specifically, the code attempts to parse a user ID from a route parameter but doesn't handle the case where the ID is not a valid integer.

The `bug.js` file contains the buggy code.  The `bugSolution.js` file provides a corrected version with robust error handling.