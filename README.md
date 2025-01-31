# Unexpected Behavior of calc() in CSS
This repository demonstrates a common issue encountered when using the `calc()` function in CSS. The problem arises when `calc()` is used to calculate a dimension based on a percentage and a fixed value, but the parent element's width is not explicitly defined.  This leads to unpredictable results.

The `bug.css` file contains the problematic CSS, while `bugSolution.css` provides a corrected version.  The solution involves ensuring the parent element has a defined width or using viewport units instead of percentages for reliable calculations.