# Unexpected calc() Behavior in CSS

This repository demonstrates an unusual issue encountered with the CSS `calc()` function when combining percentages and pixel values.  The expected behavior is not always consistent across different browsers and contexts.

The `bug.css` file contains the problematic CSS, and `bugSolution.css` illustrates potential workarounds.

## Problem

The `calc()` function, while powerful, can exhibit unexpected results when used with mixed units, particularly when percentages are involved.  This can lead to inconsistent layout and styling across different browsers or screen sizes.