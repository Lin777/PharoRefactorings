# Remove Class Refactorings

I am a refactoring for removing classes.

My precondition verifies that the class name exists in this namespace and the class has no references, resp. users, if this is used to remove a trait.

If this class is "empty" (has no methods and no variables), any subclass is reparented to the superclass of this class. It is not allowed to remove non-empty classes when it has subclasses.

## Properties

- **Class:** ```RBRemoveClassRefactoring```
- **TestClass:** ```RBRemoveClassTest```
- **Access to command:** 
    - Select class >> cmd + X
    - Select class >> open menu >> select Remove option
- [ x ] refactoring exist in Pharo 9
- [ x ] refactoring works 
- [ x ] has its own refactoring class  
- [ x ] has tests before the revision
- [ x ] has command in menu

## Analysis

- [ x ] test checked all pass
- [ ] tests were added
- [ x ] tests were refactored
- [ x ] implementation reviewed
- [ ] interaction flow todo