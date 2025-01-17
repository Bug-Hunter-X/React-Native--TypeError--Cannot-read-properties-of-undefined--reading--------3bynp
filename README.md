# React Native: TypeError: Cannot read properties of undefined (reading '...')

This repository demonstrates a common error in React Native applications where a TypeError: Cannot read properties of undefined (reading '...') occurs.  The error arises when accessing a property of an object that's undefined or null, often due to asynchronous data fetching.

## Problem

The `bug.js` file shows how this error can manifest when attempting to render data from an API call before the data has been retrieved. Accessing properties of `user` before the asynchronous operation completes results in the error.

## Solution

The `bugSolution.js` file illustrates how to resolve this issue using optional chaining (?.) and nullish coalescing (??). These operators provide a concise way to handle potentially null or undefined values.

## How to Run

1. Clone the repository.
2. Run `npm install` or `yarn install` to install dependencies.
3. Run the app using your preferred React Native development environment.