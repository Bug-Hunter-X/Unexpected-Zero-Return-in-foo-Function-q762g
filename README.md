# Unexpected Zero Return in foo Function

This repository demonstrates a subtle bug in a JavaScript function that returns 0 unexpectedly under certain conditions. The bug is related to the incorrect handling of zero inputs, potentially leading to unexpected program behavior.

## Bug Description

The `foo` function is intended to return the sum of two numbers, `a` and `b`. However, it incorrectly returns 0 if either of these numbers is 0.  While returning 0 if both are zero might be a deliberate design, the current logic causes incorrect behavior if only one input is zero.

## Bug Solution

The solution corrects this issue by only returning 0 when both inputs are zero and otherwise calculates and returns their sum.