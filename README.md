# Unhandled Promise Rejection in Node.js Express.js Application

This repository demonstrates a common error in Node.js applications using Express.js: unhandled promise rejections.  The `bug.js` file showcases an asynchronous route handler that throws an error without proper handling, leading to an unhandled promise rejection. The `bugSolution.js` file provides a solution by implementing proper error handling using a `try...catch` block or a `.catch()` method.

## Bug Description

Asynchronous operations are common in Node.js, and if these operations throw errors without proper handling, the Node.js process might crash or lead to unexpected behavior. This repository shows how to avoid such crashes using the correct error handling strategies.