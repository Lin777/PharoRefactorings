# Apply Class Deprecation Refactoring

I am a refactoring operation for removing of usages of a deprecated class, that was renamed to another name.

I'm doing following operations:
- all subclasses of the deprecated class will use the new class as superclass (optional)
- rename all references in the code
- move extensions of the deprecated class owned by other packages to the new class (optional)
- remove the extensions (optional)

## Properties

- **Class:** ```RBApplyClassDeprecationRefactoring```
- **TestClass:** ```RBApplyClassDeprecationRefactoringTest```
- **Access to command:** ???
- [ x ] refactoring exist in Pharo 9
- [ x ] refactoring works 
- [ x ] has its own refactoring class  
- [ x ] has tests before the revision
- [  ] has command in menu

## Analysis

- [ x ] test checked all pass
- [  ] tests were added
- [  ] tests were refactored
- [ ] implementation reviewed
- [ ] interaction flow todo
