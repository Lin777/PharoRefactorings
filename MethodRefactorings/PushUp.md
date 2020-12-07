# Push up Refactoring

I am a refactoring for moving a method up to the superclass. 

My precondition verify that this method does not refere to instance variables not accessible in the superclass. And this method does not sends a super message that is defined in the superclass.
If the method already exists and the superclass is abstract or not referenced anywhere, replace that implementation and push down the old method to all other existing subclasses.

## Properties

- **Class:** ```RBPullUpMethodRefactoring```
- **TestClass:** ```RBPullUpMethodTest```
- **Access to command:** 
    - select method >> open menu >> select "refactorings" option >> select "push up" option 
    - select methos >> cmd + PU
- [x] refactoring exist in Pharo 9
- [x] refactoring works
- [x] has its own refactoring class  
- [x] has tests before the revision
- [x] has command in menu

## Analysis

- [x] test checked all pass
- [] tests were added
- [x] tests were refactored
- [x] implementation reviewed
- [ ] interaction flow todo
