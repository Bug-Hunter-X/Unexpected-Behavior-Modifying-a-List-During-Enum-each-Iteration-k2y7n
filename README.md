# Elixir Enum.each Modification Bug

This example demonstrates a common misconception when using `Enum.each` in Elixir.  It attempts to modify the list being iterated over within the `each` function. This does not update the original list as one might expect in imperative languages.

The solution showcases a proper approach using `Enum.filter` or `Enum.reduce` to achieve the desired modification.