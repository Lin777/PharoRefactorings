# Generate Superclass Refactorings

Adds a new superclass between a class and its previous superclass. It offers a check-box list of the subclasses. Every checked element will be moved to be a subclass of the new superclass. That is, subclasses are moved to siblings of its prior superclass. Every instance variable shared by the new siblings will be moved to the new superclass.
The name of the new class needs to be a valid class name, not yet used as any global identifier.

## Properties

> Not implemented but this refactoring probably could use RBAddClassTest

- **Class:** ```RBAddClassTest```
- **TestClass:** ```RBAddClassRefactoring```
- **Access to command:** 
- [ ] refactoring exist in Pharo 9
- [ ] refactoring works 
- [ ] has its own refactoring class  
- [ ] has tests before the revision
- [ ] has command in menu

## Analysis

- [ ] test checked all pass
- [ ] tests were added
- [ ] tests were refactored
- [ ] implementation reviewed
- [ ] interaction flow todo