# CSS Specificity Gotcha: Nested Selectors and !important

This repository demonstrates a subtle but important CSS specificity issue related to the `!important` declaration and nested selectors.  The `!important` declaration is typically considered the highest priority, but it can be overridden by a more specific selector.

The bug is demonstrated in `bug.css`. The solution (`solution.css`) provides two strategies for handling this problem: adjusting specificity and avoiding `!important` where possible.