# Uncommon HTML Bug: Setting Height of Hidden Element

This repository demonstrates an uncommon bug in HTML related to setting the `height` style property of an element that has its `display` style set to `none`.  This issue can result in a JavaScript error in some browsers.

## Bug Description
The bug occurs when attempting to modify the `height` property of an HTML element after it has already been hidden using `display: none;`.  Some browsers might throw an error in this situation.

## Bug Reproduction
1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Click the "Click Me" button.
4. Observe the error in the browser's console (if any).

## Solution
The solution involves checking if the element is visible before attempting to modify its height. See `bugSolution.html` for a corrected version.