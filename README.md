# CSS Specificity Issue: Unexpected Style Overriding

This repository demonstrates a subtle but important CSS specificity issue related to combining ID and class selectors.  The issue can lead to unexpected style overriding when using both an ID selector and a class selector within the same element.

## Problem

The `bug.css` file contains CSS rules that highlight the issue. The selector `#specific-div.container` unexpectedly overrides the style set by the `#specific-div` selector because it is more specific due to the combination of ID and class selectors.

## Solution

The `bugSolution.css` file offers a solution. Understanding how specificity works in CSS is critical to avoiding such problems.