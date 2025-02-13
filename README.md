# JavaScript Division by Zero Error

This repository demonstrates a common JavaScript error: division by zero. The `bug.js` file contains the erroneous code, while `bugSolution.js` provides a corrected version with proper error handling.

## Bug

The original code lacks error handling for division by zero.  This results in an unhandled exception when the `divide` function is called with a divisor of 0.

## Solution

The solution adds a conditional statement to check if the divisor is zero. If it is, an error is thrown to prevent the program from crashing.  This provides robust error handling, making the function more reliable.

## How to Run

1. Clone the repository.
2. Navigate to the directory.
3. Run the JavaScript files using Node.js (or a similar JavaScript runtime): 
   ```bash
   node bug.js
   node bugSolution.js
   ```