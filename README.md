# F# Mutability and Unexpected Behavior

This example demonstrates how mutable variables in F# can lead to unexpected behavior if not handled carefully. The variable `z` is initially calculated based on the values of `x` and `y`, but changing `x` later doesn't update `z`. This highlights the difference between mutable and immutable variables in F# and how to avoid common pitfalls.