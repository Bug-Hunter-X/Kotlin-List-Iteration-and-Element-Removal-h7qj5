# Kotlin List Iteration and Element Removal

This example demonstrates a common mistake when removing elements from a Kotlin MutableList while iterating.  Incorrectly modifying the list during iteration using a for loop or standard iterator can lead to a `ConcurrentModificationException`. 

The provided code showcases two methods to avoid this issue: using the built-in `removeIf` function and using an iterator's `remove()` method correctly.

## How to run the code

1. Save the code as `bug.kt` and `bugSolution.kt`
2. Compile and run the Kotlin code using your preferred Kotlin compiler (e.g., Kotlin/JVM).
