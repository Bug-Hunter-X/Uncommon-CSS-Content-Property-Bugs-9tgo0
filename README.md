# Uncommon CSS Content Property Bugs

This repository demonstrates some uncommon bugs related to the CSS `content` property, specifically focusing on unexpected behavior, specificity issues, and misuse of the `attr()` function within the `content` property.  The `bug.css` file showcases the problematic code, while `bugSolution.css` provides solutions and explanations.

## Bugs Demonstrated:

1. **Unexpected behavior with `content` and pseudo-elements:**  Missing or incorrectly used values in conjunction with `::before` or `::after` can lead to errors or inconsistent rendering.
2. **Specificity Conflicts:** When generated content is involved, resolving specificity conflicts between different selectors can be challenging and cause unexpected styling issues.
3. **Incorrect use of `attr()` function:** Incorrectly handling attributes or non-existent attributes within `attr()` can lead to errors or incorrect rendering of content.