# Unexpected Instance Variable Behavior in Ruby

This repository demonstrates an uncommon yet easily encountered bug in Ruby related to modifying instance variables.  The `bug.rb` file shows how trying to set an instance variable using the getter method fails to update the actual instance variable.  The `bugSolution.rb` file demonstrates the correct approach.

This is a subtle error because it might not immediately throw an exception. Instead, it leads to unexpected and hard-to-debug behavior if you rely on the getter method for updates.