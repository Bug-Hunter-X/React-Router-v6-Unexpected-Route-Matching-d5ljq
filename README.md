# React Router v6 Unexpected Route Matching

This repository demonstrates a common issue encountered when using React Router v6: unexpected route matching and navigation problems.  Routes might not match their intended paths, resulting in incorrect component rendering or navigation failures.  The example showcases this issue and provides a solution.

## Problem

In the provided `bug.js` file, observe the standard React Router setup.  The intended behavior is straightforward: 

* `/`: Renders the `Home` component.
* `/about`: Renders the `About` component.
* Any other path: Renders the `NotFound` component.

However, due to subtle configuration errors (often related to path specificity or order of routes), unexpected matching might occur, which breaks routing and leads to incorrect pages being displayed.

## Solution

The `bugSolution.js` file presents a corrected version.  By carefully reviewing the path definitions and route order, the routing logic is fixed.

## Setup

1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.   Navigate between `/`, `/about`, and other paths to observe the differences.