# What is Swifter?

Tiny http server engine written in [Swift](https://developer.apple.com/swift/) programming language. The source repository is [httpswift/swifter](https://github.com/httpswift/swifter).

## Why this fork?

The source repository, as per README, supports Carthage only at version `1.4.0`, however this seems to have broken at some point.

This fork is an attempt to restore Carthage compatibility by moving the project in the top-most folder, so that Carthage can recompile the project when needed.

**Warning**: This is only supported for the `stable` branch.

### How to Carthage

`github "marcoconti83/swifter" "stable"`