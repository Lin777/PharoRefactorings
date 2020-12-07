# Remove parameter Refactoring

I am a refactoring for removing (unused) arguments.

My preconditions verify that the argument to be removed is not referenced by the methods and that the new method name isn't alread used.
Any sender of the prior selector will be changed to the new.

If the method contains more than one argument, I request the user to choose one of the arguments.

## Properties

> Not works

- **Class:** ```RBRemoveParameterRefactoring```
- **TestClass:** ```RBRemoveParameterTest```
- **Access to command:** 
    - select method >> open menu >> select "refactoring" option >> select "Remove argument" option
- [x] refactoring exist in Pharo 9
- [x] refactoring works
- [x] has its own refactoring class  
- [x] has tests before the revision
- [x] has command in menu

## Analysis

- [x] test checked all pass
- [x] tests were added
- [ ] tests were refactored
- [ ] implementation reviewed
- [ ] interaction flow todo
