# Unexpected Float Behavior in CSS

This repository demonstrates an uncommon issue with the `float` property in CSS.  The issue occurs when a floated element's width is not an even divisor of its parent container's width. Some browsers may render the layout incorrectly.

The `bug.css` file shows the problematic CSS, while `bugSolution.css` presents a solution using flexbox, avoiding the problematic `float` behavior. 

This issue highlights the importance of carefully considering layout behavior across different browsers and using more robust layout methods like flexbox for consistent results.