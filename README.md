# CSS `calc()` Gotcha

This repository demonstrates a common, yet subtle, issue with the CSS `calc()` function. The problem arises from a misunderstanding of operator precedence and the importance of consistent unit usage within the `calc()` expression.

## The Bug

The `calc()` function, while powerful, can lead to unexpected results if you're not careful.  Incorrect order of operations and inconsistent units can both lead to incorrect calculations by the browser.

## The Solution

Carefully review your `calc()` expressions, paying close attention to:

1. **Operator Precedence:** Use parentheses `()` to explicitly define the order of operations.
2. **Unit Consistency:** Ensure that you are using compatible units throughout your `calc()` expression.  Avoid mixing percentages with pixel values without explicit unit conversions.

Following these guidelines helps prevent the common `calc()` calculation errors.