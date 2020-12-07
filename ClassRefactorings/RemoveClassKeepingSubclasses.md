# Remove Class Keeping Subclasses Refactoring

I am a refactoring for removing classes but keeping subclasses in a safe way.

My precondition verifies that the class name exists in this namespace and the class has no references, resp. users, if this is used to remove a trait.

If this class is "not empty" (has methods and variables), any subclass is reparented to the superclass of this class, and all its methods and variables (instance and class) are push down in its subclasses.

## Properties

- **Class:** ```RBRemoveClassKeepingSubclassesRefactoring```
- **TestClass:** ```RBRemoveClassKeepingSubclassesTest```
- **Access to command:** 
    - Select class >> open menu >> select "Remove keeping subclasses" option
- [x] refactoring exist in Pharo 9
- [x] refactoring works 
- [x] has its own refactoring class  
- [x] has tests before the revision
- [x] has command in menu

## Analysis

- [x] test checked all pass
- [ ] tests were added
- [ ] tests were refactored
- [ ] implementation reviewed
- [ ] interaction flow todo

## Notes

- Need add more tests