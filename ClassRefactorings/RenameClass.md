# Rename Class Refactorings

I am a refactoring for renaming a class.

My preconditions verify, that the old class exists (in  the current namespace) and that the new class name is valid and not yet used as a global variable name

The refactoring transformation will replace the current class and its definition with the new class name. And update all references in all methods in this namespace, to use the new name. Even the definition for subclasses of the old class will be changed.

Example
---------------

``` Smalltalk
(RBRenameClassRefactoring rename: RBRenameClassRefactoring to: 'RBRenameClassRefactoring2') execute
```

## Properties

- **Class:** ```RBRenameClassRefactoring```
- **TestClass:** ```RBRenameClassTest``` 
- **Access to command:** 
    - Select class >> cmd + R
    - Select class >> open menu >> select Rename option
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