# Replace Method Refactoring

I'm a refactoring operation for replace one method call by another one.

The another method name should have the same number of arguments.

All senders of this method are changed by the other

## Properties

- **Class:** ```RBReplaceMethodRefactoring```
- **TestClass:** ```RBReplaceMethodTest```
- **Access to command:** 
    - select method >> open menu >> select "refactoring" option >> select "replace senders" option
- [x] refactoring exist in Pharo 9
- [x] refactoring works
- [x] has its own refactoring class 
- [x] has tests before the revision
- [x] has command in menu

## Analysis

- [x] test checked all pass
- [ ] tests were added
- [x] tests were refactored
- [ ] implementation reviewed
- [ ] interaction flow todo