# Push down Refactoring

I am a refactoring for moving a method down to all direct subclasses.

My preconditions verify that this method isn't refered  as a super send in the subclass. And the class defining this method is abstract or not referenced anywhere.

## Properties

- **Class:** ```RBPushDownMethodRefactoring```
- **TestClass:** ```RBPushDownMethodTest```
- **Access to command:** 
    - select method >> open menu >> select "refactorings" option >> select "push down" option 
    - select methos >> cmd + PD
- [x] refactoring exist in Pharo 9
- [x] refactoring works
- [x] has its own refactoring class  
- [x] has tests before the revision
- [x] has command in menu

## Analysis

- [x] test checked all pass
- [x] tests were added
- [ ] tests were refactored
- [x] implementation reviewed
- [ ] interaction flow todo
