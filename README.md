# Unexpected Behavior from Directly Accessing Instance Variables in Ruby

This example demonstrates a potential issue when directly manipulating instance variables in Ruby using `instance_variable_set`. While it might seem convenient, it can lead to unexpected behavior and make the code harder to maintain.

**Problem:** Directly altering instance variables bypasses the class's methods designed for controlling access and modification, potentially causing inconsistency and making debugging difficult.

**Solution:** Use accessor methods (getters and setters) to modify instance variables for better encapsulation and maintainability.