# F# Mutable Variable Swap Bug

This repository demonstrates a common error in F# involving mutable variables and unexpected behavior when attempting to swap their values.

The `bug.fs` file contains code that attempts to swap two mutable integer variables using a function. However, due to how mutable variables are handled in F#, the result is different from what one might initially expect.

The `bugSolution.fs` file provides the corrected code using a tuple to achieve the desired value swap, demonstrating the correct approach.

This example highlights the importance of understanding how mutable variables are passed and manipulated within F# functions.