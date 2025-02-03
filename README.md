# React Native useState Hook: Direct Mutation of Object/Array State

This repository demonstrates a common error when using the `useState` hook in React Native with objects or arrays.  Directly modifying these values (e.g., using `push`, `splice`, or directly assigning properties) does not trigger a re-render because React performs a shallow comparison, and the object/array reference remains unchanged.

The `bug.js` file shows the problematic code, and `bugSolution.js` provides the correct approach, ensuring the UI updates correctly.