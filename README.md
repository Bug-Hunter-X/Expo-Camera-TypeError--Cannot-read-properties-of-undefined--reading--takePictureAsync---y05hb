# Expo Camera Initialization Error

This repository demonstrates a common error encountered when using the Expo Camera API: a TypeError indicating that the camera object is undefined.  The issue arises from attempting to use camera functions before the camera has finished initializing.

The `bug.js` file showcases the problematic code, while `bugSolution.js` provides the corrected version.  This example uses asynchronous operations and proper error handling to resolve the issue.

## How to Reproduce

1. Clone this repository.
2. Install dependencies: `npm install` or `yarn install`
3. Run the `bug.js` example and observe the error.
4. Run the `bugSolution.js` example to see the corrected implementation.