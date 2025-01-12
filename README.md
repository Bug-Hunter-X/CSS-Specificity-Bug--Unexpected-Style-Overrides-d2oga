# CSS Specificity Bug: Unexpected Style Overrides

This repository demonstrates a common CSS bug related to specificity.  A more specific selector unintentionally overrides a more general style that should have precedence. The `bug.css` file contains the problematic code, while `bugSolution.css` shows the corrected version.

## Bug Description

The issue is that an inline style or a highly specific selector overrides a style that should have precedence based on the cascading order. This can be difficult to debug, as the browser doesn't always clearly indicate the source of the conflict.

## How to Reproduce

1.  Open `bug.html` in your web browser.
2. Observe that the paragraph text is red, despite the general style specifying blue.

## Solution

The solution involves carefully reviewing and adjusting selectors to ensure the appropriate specificity and cascading order.  The `bugSolution.css` file demonstrates the corrected CSS.