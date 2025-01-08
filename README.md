# React Router Dom v6 Catch-all Route '*' issue

This repository demonstrates a common issue encountered when using the catch-all route ('*') in React Router Dom v6.  The catch-all route is intended to match any path not explicitly defined, however, it sometimes fails to behave as expected.  The issue might be seen when unexpected routing behaviors occur when using nested routes or client-side navigation.

## Problem
The provided example shows a simple React Router setup.  Even though a catch-all route is included, it may not be triggered when navigating to a path that doesn't match any of the defined routes. This can lead to unexpected behavior and a poor user experience.

## Solution
The solution involves ensuring the catch-all route is correctly positioned within the routes configuration to handle unexpected paths effectively.  Additionally, we demonstrate how to use `useLocation` hook to better understand the current URL and provide more effective error handling.