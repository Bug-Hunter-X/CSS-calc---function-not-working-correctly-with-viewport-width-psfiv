# CSS calc() Issue with Viewport Width

This repository demonstrates a problem with the `calc()` function in CSS when attempting to calculate a width based on the viewport width and subtracting a fixed value.  The expected behavior is that the element's width should be the viewport width minus 20 pixels.  However, the actual result is different.

## Bug Report

The `bug.css` file contains the CSS code causing the issue. The `bugSolution.css` file provides the fix.

## Steps to Reproduce

1.  Create an HTML file and link to `bug.css`.
2.  Add an element with the class `element` to the HTML.
3.  Observe the element's width. It will not be the viewport width minus 20px.

## Solution

The issue was resolved by adding spaces around the minus operator within the `calc()` function. The corrected code is provided in `bugSolution.css`.