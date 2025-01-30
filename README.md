# Unexpected Continue Statement Behavior in Java

This repository demonstrates a subtle and potentially unexpected behavior of the `continue` statement within a `while` loop in Java.  The provided code intends to skip printing the number 5, but the behavior might not be immediately intuitive to all Java developers, especially those newer to the language.

## Problem Description

The `continue` statement in a loop immediately jumps to the next iteration, bypassing any remaining code within the current iteration. While seemingly straightforward, its interaction with other loop control structures can lead to unexpected results if not carefully considered.

## Solution

The solution demonstrates a clearer and more predictable way to achieve the desired behavior by using an `if` statement to directly control what values are printed.  This approach reduces potential confusion and promotes more robust code.

## How to Run

1. Clone this repository.
2. Compile the Java files using a Java compiler (e.g., `javac Bug.java` and `javac BugSolution.java`).
3. Run the compiled Java files (e.g., `java Bug` and `java BugSolution`).

Observe the output from both files to understand the differences between the original problematic code and the improved solution.