# Abstract Instance Variable Refactoring

I am a refactoring for replacing every direct access to  instance  variables with accessor methods.

My precondition verifies that the variable is directly defined in that class.
I create new accessor methods for the variables and replace every read and write to this variable with the new accessors.

## Properties

- **Class:** ```RBAbstractInstanceVariableRefactoring```
- **TestClass:** ```RBAbstractInstanceVariableTest```
- **Access to command:** 
    - Select class >> open menu >> select "Abstract instance variables" option
- [ x ] refactoring exist in Pharo 9
- [  ] refactoring works 
- [ x ] has its own refactoring class  
- [ x ] has tests before the revision
- [ x ] has command in menu

## Analysis

- [ x ] test checked all pass
- [ x ] tests were added
- [  ] tests were refactored
- [ x ] implementation reviewed
- [ ] interaction flow todo

## Notes

- This refactoring works bad, somethimes only replace some variables not all
