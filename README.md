# Unexpected Process Exit in Elixir Enum.each

This example demonstrates a potential issue when using `Process.exit` within an `Enum.each` loop in Elixir.  Improper use of `Process.exit` can lead to unexpected termination of the enumeration before all elements have been processed.

The `bug.ex` file contains the buggy code. The `bugSolution.ex` file shows the corrected approach.