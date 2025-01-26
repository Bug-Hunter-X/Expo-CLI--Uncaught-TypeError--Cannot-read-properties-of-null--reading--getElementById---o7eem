# Expo CLI: Uncaught TypeError: Cannot read properties of null (reading 'getElementById')
This repository demonstrates a common error when working with Expo and React Native: attempting to use `document.getElementById` to interact with the DOM.  React Native uses a different rendering mechanism, and direct DOM manipulation isn't supported.

The `bug.js` file shows the problematic code. The `bugSolution.js` file offers a corrected approach using React Native's state management and component lifecycle methods to achieve the desired behavior.  The solution avoids direct DOM access.

## How to Reproduce
1. Clone this repository.
2. Navigate to the project directory: `cd expo-dom-error`
3. Run the Expo project: `expo start`
4. Observe the error in the console (if using `bug.js`).
5. Replace `bug.js` with `bugSolution.js` and run again to see the corrected behavior.