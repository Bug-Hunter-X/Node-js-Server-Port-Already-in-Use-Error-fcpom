# Node.js Server Port Already in Use Error

This repository demonstrates a common error encountered when developing Node.js applications: attempting to start a server on a port that's already in use.  The error message from Node.js can sometimes be cryptic, leading to debugging challenges.

The `bug.js` file contains the faulty code.  The `bugSolution.js` demonstrates a robust way to handle this situation, providing a more user-friendly experience.

## How to Reproduce

1. Clone this repository.
2. Run `node bug.js`.  If port 8080 is free, the server will start.  If not (e.g., another application is using it), an error will occur.
3. Run `node bugSolution.js` to see the improved error handling.