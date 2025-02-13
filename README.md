# Ruby: Direct Access to Instance Variables

This example demonstrates the potential issue of directly accessing instance variables using `instance_variable_get` in Ruby. While this works, it bypasses the getter/setter methods and can lead to issues with maintainability and debugging.

The `bug.rb` file showcases the direct access. The `bugSolution.rb` illustrates using getter and setter methods.