# React useState Hook: Direct Modification of State Variable

This repository demonstrates a common error when working with the `useState` hook in React: directly modifying the state variable.

## The Problem
The `useState` hook returns an array: the current state value and a function to update it.  Attempting to update the state variable directly will not trigger a re-render and will lead to unexpected behavior.  The provided example shows this incorrect approach.

## The Solution
The correct way to update the state is to always use the setter function.  This ensures React's internal mechanisms are triggered, leading to correct re-rendering and state management.

## How to run
1. Clone the repo
2. Navigate to the directory
3. run `npm install`
4. run `npm start`