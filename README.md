# Swift Function Call Error: Missing Parameter Label

This repository demonstrates a common error in Swift: incorrect function calls due to missing parameter labels. The example shows a function with labeled parameters and how to call it correctly and incorrectly.

## Bug
The function `calculateArea` requires both `width` and `height` parameters to be labeled. The second call to the function omits the label for `height`, causing a compilation error.

## Solution
The solution involves calling the function correctly by including all parameter labels.