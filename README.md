# React Router v6 Catch-All Route Issue

This repository demonstrates a problem with React Router v6's catch-all route (`/*`).  When navigating to a non-existent route, the `NotFound` component, intended to handle such cases, is not displayed.

## Bug
The provided `bug.js` file shows a basic React Router setup. Despite the `/*` route, navigating to an invalid URL results in unexpected behavior instead of showing the '404' page.

## Solution
The solution involves ensuring the correct usage of `Routes` and `Route` components.  See `bugSolution.js` for the corrected implementation.