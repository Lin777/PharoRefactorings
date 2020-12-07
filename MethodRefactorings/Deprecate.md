# Deprecate Refactoring

I am a refactoring to mark a method as deprecated and replace the implementation by a call to a new method.

oldSelector
	- is a selector which shouldn't be used anymore, it's deprecated
newSelector
	- is a selector which will be used instead of a deprecated one

The implementation of oldSelector is replaced by a call to ```#deprecated:on:in:``` and the newSelector.

The message ```#deprecated:on:in:```  will be used to inform the user about the deprecation.

### Note 
It is recommended to use this refactoring only if number of arguments is either equal in both selectors, or the new one has no arguments at all.
If new selector has fewer number of arguments than the old one, it may lead to unexpected results.
If you use it in other conditions an error may be be occured.

## Properties

- **Class:** ```RBDeprecateMethodRefactoring```
- **TestClass:** ```RBDeprecateMethodTest```
- **Access to command:** ???
- [x] refactoring exist in Pharo 9
- [x] refactoring works 
- [x] has its own refactoring class  
- [ ] has tests before the revision
- [ ] has command in menu

## Analysis

- [x] test checked all pass
- [x] tests were added
- [ ] tests were refactored
- [ ] implementation reviewed
- [ ] interaction flow todo
