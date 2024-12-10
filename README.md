# Kotlin removeIf() Unexpected Behavior

This repository demonstrates an uncommon error that can occur when using the `removeIf()` function with a `MutableList` in Kotlin.  The `removeIf()` function modifies the list in-place while iterating over it. If not handled correctly, this can result in elements being skipped and unexpected results.

The `bug.kt` file contains code that reproduces the issue, and `bugSolution.kt` provides a corrected solution demonstrating how to avoid this problem.

This is a common pitfall for developers unfamiliar with the intricacies of in-place modification during iteration.