# Add Parameter Refactoring

I am a refactoring operations for adding method arguments.

You can modify the method name and add an additional keyword argument and the default value used by senders of the original method. Only one new argument can be added. But you can change the whole method name, as long as the number of argument matches.

For example, for r:g:b:  add another parameter "a" the new method is r:g:b:a:
or change the whole method to setRed:green:blue:alpha:

This refactoring will
•	add a new method with the new argument,
•	remove the old method (for all implementors) and
•	replace every sender of the prior method with the new one, using the specified default argument.

## Properties

- **Class:** ```RBAddParameterRefactoring```
- **TestClass:** ```RBAddParameterTest```
- **Access to command:** 
    - Select method >> open menu >> select "Refactorings" option >> select "Add argument" option
- [x] refactoring exist in Pharo 9
- [x] refactoring works 
- [x] has its own refactoring class  
- [x] has tests before the revision
- [x] has command in menu

## Analysis

- [x] test checked all pass
- [x] tests were added
- [x] tests were refactored
- [x] implementation reviewed
- [ ] interaction flow todo
