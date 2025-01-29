# Unexpected Routing Behavior with Nested Routes and Parameters in React Router Dom v6

This repository demonstrates an unexpected behavior encountered when using nested routes with parameters in React Router Dom v6.  The issue arises when a nested route containing parameters is defined, even if the parent route is correctly matched.  This leads to unexpected routing or rendering issues.

## Bug Description

The provided code includes a simple React app using React Router v6.  When navigating to `/users/:userId`, the route does not work as expected.  This is likely due to an interaction between the route definition and parameter matching within a nested structure.

## How to Reproduce

1. Clone this repository.
2. Install dependencies using `npm install`.
3. Run the app using `npm start`.
4. Navigate to `/users/123` (or any other userId).

Observe that the route rendering is incorrect or does not match the expected behavior. This demonstrates the bug reported.