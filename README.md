# React useEffect Hook with Missing Dependency

This repository demonstrates a common bug in React applications involving the `useEffect` hook.  The bug arises from an incorrectly specified or missing dependency array, leading to unexpected behavior and, in some cases, an infinite render loop.

The `bug.js` file contains the buggy code, while `bugSolution.js` provides the corrected implementation.  The core issue involves the `useEffect` hook not re-rendering correctly because of missing dependencies in the dependency array.