# Unresponsive Node.js Server

This repository demonstrates a common issue in Node.js where a long-running task within the request handler can block the event loop, leading to an unresponsive server. The `bug.js` file shows the problematic code, while `bugSolution.js` provides a corrected version using asynchronous operations.