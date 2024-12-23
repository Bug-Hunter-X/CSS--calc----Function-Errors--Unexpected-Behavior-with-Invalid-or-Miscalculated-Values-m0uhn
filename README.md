# CSS `calc()` Function Errors
This repository demonstrates a common error when using the CSS `calc()` function: producing invalid or unexpected results due to negative values or incorrect operator precedence.  The `bug.css` file shows the problematic code, while `bugSolution.css` provides the corrected version.

**Problem:** The `calc()` function produces a negative value that causes unexpected behavior.  Understanding the order of operations and ensuring the calculation produces a valid CSS value is crucial for preventing this issue. 

**Solution:** Carefully review the calculation within the `calc()` function to ensure it always produces a positive, valid value. Consider using `max()` or `min()` to handle scenarios where the calculation might result in negative or unexpected values.