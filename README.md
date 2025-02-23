# Uncommon HTML Bug: Incorrect innerHTML Usage

This repository demonstrates an uncommon bug that can occur in HTML when using the `innerHTML` property incorrectly.  The bug arises from assigning a non-string value (in this case, a number) to `innerHTML`.  This can lead to unexpected behavior or errors in the browser, as `innerHTML` expects a string value.

## Bug Description
The `bug.html` file contains a simple HTML page with a div element and a JavaScript script that attempts to assign the number 123 to the `innerHTML` property of the div. This is incorrect and can result in the div not being updated as expected or even throwing errors in some browsers.

## Bug Solution
The `bugSolution.html` file provides the correct solution. The number 123 is explicitly converted to a string using the `String()` function before being assigned to `innerHTML`. This ensures that the value is properly handled by the browser and that the content of the div is updated correctly.
