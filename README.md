# JavaScript Loose Comparison and Null Handling

This repository demonstrates a common JavaScript bug related to loose comparison and null handling. Loose comparison (==) in JavaScript can lead to unexpected results when comparing values, especially when dealing with null or undefined.

## The Bug
The `foo` function intends to add two numbers. However, it fails to correctly handle `null` values due to loose comparison.

## The Solution
The solution uses strict equality (`===`) to explicitly check for `null` values, preventing unintended type coercion and resulting in accurate null handling.

## How to reproduce
1. Clone this repository.
2. Open `bug.js` to see the buggy code.
3. Open `bugSolution.js` to see the corrected code. 
4. Run the JavaScript files (e.g., using Node.js) to observe the difference in behavior.