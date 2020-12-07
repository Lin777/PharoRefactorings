# Rename Refactoring

I am a refactoring operation for renaming methods.

The new method name has to have the same number of arguments, but the order of arguments can be changed.

My preconditions verify that the number of arguments is the same and that the new method name isn't already used.

All references in senders of the old method are changed, either the method name only or the order of the supplied arguments.

## Properties

- **Class:** ```RBRenameMethodRefactoring```
- **TestClass:** ```RBRenameMethodTest```
- **Access to command:** 
    - select method >> open menu >> select "rename" option
    - select method >> cmd + R
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
