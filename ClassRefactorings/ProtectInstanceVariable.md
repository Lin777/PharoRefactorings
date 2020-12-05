# Protect Instance Variable Refactoring

I am a refactoring for protecting instance variable access.

If a class defines methods for reading and writing instance variables, they are removed and all calls on this methods.
Omit method that are redefined in subclasses.

## Properties

- **Class:** ```RBProtectInstanceVariableRefactoring```
- **TestClass:** ```RBProtectInstanceVariableTest```
- **Access to command:** ???
- [ x ] refactoring exist in Pharo 9
- [ x ] refactoring works 
- [ x ] has its own refactoring class  
- [ x ] has tests before the revision
- [  ] has command in menu

## Analysis

- [ x ] test checked all pass
- [  ] tests were added
- [  ] tests were refactored
- [ x ] implementation reviewed
- [ ] interaction flow todo

## Note

- Need add more tests