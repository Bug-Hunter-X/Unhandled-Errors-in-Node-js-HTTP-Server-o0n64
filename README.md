# Node.js HTTP Server Error Handling

This repository demonstrates a common error in Node.js applications: unhandled exceptions in HTTP servers. The `server.js` file shows a basic HTTP server without proper error handling. The `server-solution.js` file provides an improved version with comprehensive error handling.

## Problem

The original `server.js` lacks error handling. If an exception occurs during request processing, the server crashes, leading to downtime and potential data loss. 

## Solution

The `server-solution.js` demonstrates how to implement robust error handling using `try...catch` blocks and event listeners for server errors. This prevents crashes and allows for graceful handling of unexpected situations.