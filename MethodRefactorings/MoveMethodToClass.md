
# Move Method To Class Refactoring

A RBMoveMethodToClassRefactoring is a class that represents functionality of "Move method to class" refactoring.
User chooses method, and than any of existiong classes.
Refactoring moves chosen method to class.

Instance Variables
method:  <RBMethod>

method
- chosen method

## Properties

- **Class:** ```RBMoveMethodToClassRefactoring```
- **TestClass:** ```RBMoveMethodToClassTest```
- **Access to command:** 
    - select method >> open menu >> select "refactoring" option >> select "Move to class side" option
    - select method >> open menu >> select "refactoring" option >> select "Move to another class" option
    - select method >> open menu >> select "refactoring" option >> select "Move to instance side" option
- [x] refactoring exist in Pharo 9
- [x] refactoring works
- [x] has its own refactoring class  (generic for N commands)
- [x] has tests before the revision
- [x] has command in menu

## Analysis

- [x] test checked all pass
- [ ] tests were added
- [ ] tests were refactored
- [ ] implementation reviewed
- [ ] interaction flow todo

## Notes

> Need add more tests