# CSS Specificity Bug

This repository demonstrates a common CSS issue related to specificity.  The `bug.css` file contains a style rule that is being unintentionally overridden due to a higher-specificity rule elsewhere (possibly in a linked stylesheet or within the HTML itself). The solution shows how to correct this using a more specific selector.

## How to Reproduce

1. Open `bug.html` in your web browser.
2. Observe that the text's styling does not match what is intended in `bug.css`.

## Solution

The solution is provided in `bugSolution.css`. By carefully reviewing the CSS specificity rules, a more specific selector is implemented in the solution to ensure the intended styling overrides the existing style, resolving the unexpected styling.