# Uncommon HTML Error: Typo in getElementById

This repository demonstrates a subtle but common error in HTML/JavaScript: a simple typo in the `getElementById` function. This can lead to unexpected behavior and runtime errors.

The `bug.html` file contains the erroneous code.  The `solution.html` file provides the correct implementation.

## How to reproduce the bug

1. Open `bug.html` in a web browser.
2. Observe the error message in the browser's developer console.
3. Note that the div with the id "myDiv" will not be updated.

## How to fix the bug

Correctly use `getElementById` to access and modify elements within the DOM (Document Object Model).