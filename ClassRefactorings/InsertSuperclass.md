# Insert SuperClass Refactorings

Similar to "Generate Superclass", but just generates a new class between a class and its previous superclass. With no change on the subclass hierarchy of the class.
The name of the new class needs to be a valid class name, not yet used as any global identifier.

## Properties
> This refactoring use a generic class: RBAddClassTest

- **Class:** ```RBAddClassTest```
- **TestClass:** ```RBAddClassRefactoring```
- **Access to command:** 
    - Select class >> open menu >> select "Refactorings" option >> select "Insert superclass" option
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
