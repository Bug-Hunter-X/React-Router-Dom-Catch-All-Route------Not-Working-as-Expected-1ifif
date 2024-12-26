## React Router Dom Catch-All Route Issue

This repository demonstrates a subtle bug in React Router Dom v6 where the catch-all route `/*` doesn't function correctly in specific scenarios.  The issue occurs when certain routes are defined before the catch-all route, causing it to be ignored even when no other routes match.

The `App.js` file shows the problematic code.  The `AppSolution.js` file provides a corrected implementation.

This issue is particularly hard to debug because it doesn't always manifest, only appearing in certain combinations of routes.

This repo aims to document this edge case and provide a potential solution.