# Uncommon HTML Bug: innerHTML on Non-Existent Element

This repository demonstrates a subtle bug that can occur in HTML when using `innerHTML` on an element that doesn't exist in the DOM.  The JavaScript error might not be immediately obvious, and it could cause unexpected behavior in larger applications.

## The Bug
The `bug.html` file contains the problematic code.  It attempts to set the `innerHTML` of an element with the ID 'nonExistentElement'. Since this element does not exist, a JavaScript error is thrown. 

## The Solution
The `solution.html` file provides a corrected version.  It first checks if the element exists before attempting to modify its `innerHTML`, preventing the error.  Always validate element existence before working with it!