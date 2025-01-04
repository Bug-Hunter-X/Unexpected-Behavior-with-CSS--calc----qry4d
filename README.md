# Unexpected Behavior with CSS `calc()`

This repository demonstrates an uncommon issue that can arise when using the CSS `calc()` function. Specifically, it highlights problems related to operator precedence and the importance of proper spacing and unit consistency within the `calc()` expression.

## Bug Description:
The `calc()` function in CSS allows dynamic calculations within style declarations. However, if not used carefully, this can lead to unexpected results due to issues with operator precedence and inconsistent units.  The primary problem demonstrated is caused by a missing space between the operator and the operands and incorrect unit handling.

## How to Reproduce:
Clone this repository and open `bug.css` and observe the unexpected rendering of the elements.