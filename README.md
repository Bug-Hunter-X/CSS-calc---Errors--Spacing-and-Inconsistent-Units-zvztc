# CSS calc() Errors: Spacing and Inconsistent Units

This repository demonstrates two uncommon errors related to the CSS `calc()` function:

1. **Incorrect Spacing:**  A space between the percentage and the operator (e.g., `100% -`) can break the calculation in some browsers.
2. **Inconsistent Units:** Mixing units within `calc()` (e.g., `px` and `em`) without proper conversion can cause unexpected results.

The `bug.css` file contains the erroneous code, while `bugSolution.css` shows the corrected version.