# CSS Pseudo-element Selector Bug

This repository demonstrates a subtle but important bug in CSS related to the use of pseudo-element selectors. The bug involves the incorrect usage of the `:before` and `::before` pseudo-elements.  While superficially similar, the double colon (`::`) is crucial for correct behavior.

The `bug.css` file contains the incorrect code, which might render differently across browsers or lead to unexpected results. The `bugSolution.css` file contains the corrected version, highlighting the proper use of `::before`.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in your browser.
3. Observe the unexpected behavior caused by the incorrect CSS.
4. Compare it with the corrected version in `bugSolution.html`.

## Solution

Always use the double colon (`::`) notation for pseudo-elements (e.g., `::before`, `::after`).  The single colon (`:`) is reserved for pseudo-classes.