# Accessing Private Variables in Scala

This example illustrates a potential issue when working with private variables in Scala classes.  The `MyClass` example has a private variable `internalValue` and provides methods to update and retrieve its value.  Attempting direct access to `internalValue` from outside the class will result in a compilation error, enforcing encapsulation.