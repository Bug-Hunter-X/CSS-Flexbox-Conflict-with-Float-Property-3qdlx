# CSS Flexbox Conflict with Float Property

This repository demonstrates a common CSS issue where using `display: flex;` on a floated element leads to unpredictable behavior.  The `float` property conflicts with `display: flex;`, resulting in layout inconsistencies.  The solution shows how to resolve this conflict by removing the `float` property and using flexbox properties to achieve the desired layout.

## Bug

The `bug.css` file contains the problematic CSS rule applying both `float` and `display: flex;` to the same element. This results in incorrect rendering in many browsers.

## Solution

The `bugSolution.css` file shows the corrected CSS.  The `float` property is removed, and flexbox properties are used to manage the element's position and alignment. 

This demonstrates the importance of understanding flexbox layout and avoiding conflicts with other CSS properties that might interfere with its intended behavior.