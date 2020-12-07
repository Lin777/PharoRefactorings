# Generate subclass Refactorings

Adds a new class as a subclass of the selected class. It offers a check box list of the subclasses. Every checked element will be moved to be a sub-subclass of the new subclass. The hierarchy of the not checked elements is unchanged and they become siblings of the new class.
The name of the new class needs to be a valid class name, not yet used as any global identifier.

## Properties
> This refactoring use a generic class: RBAddClassTest

- **Class:** ```RBAddClassTest```
- **TestClass:** ```RBAddClassRefactoring```
- **Access to command:** 
    Select class >> open menu >> select "Refactorings" option >> select "New subclass" option
- [x] refactoring exist in Pharo 9
- [x] refactoring works 
- [ ] has its own refactoring class  
- [x] has tests before the revision
- [x] has command in menu

## Analysis

- [x] test checked all pass
- [x] tests were added
- [ ] tests were refactored
- [x] implementation reviewed
- [ ] interaction flow todo
