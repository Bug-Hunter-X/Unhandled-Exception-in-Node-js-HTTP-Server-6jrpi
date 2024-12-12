# Unhandled Exception in Node.js HTTP Server

This repository demonstrates a common error in Node.js: failure to handle exceptions properly in an HTTP server.  The `bug.js` file shows the problematic code, while `bugSolution.js` presents a corrected version with robust error handling.

The original code lacks error handling, making it vulnerable to crashes from unexpected events.

The solution incorporates `try...catch` blocks to gracefully handle potential errors and prevents the server from crashing.