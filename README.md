# F# Mutability Bug

This example demonstrates a common pitfall in F# related to mutable variables.  The `swap` function attempts to swap the values of two mutable variables, but due to how mutability is handled, the outcome is not what one might initially expect. The solution highlights a safer approach using immutability.