# Rename Class Variable

I am a refactoring for rename class variables.

I rename the class variable in the class definition and in all methods refering to this variable.

My precondition verifies that the new variable is valid and not yet used in the whole class hierarchy.

## Properties

- **Class:** ```RBRenameClassVariableRefactoring```
- **TestClass:** ```RBRenameClassVariableTest```
- **Access to command:** 
    - Select class variable >> cmd + R
    - Select class variable >> open menu >> select "Rename" option
- [ x ] refactoring exist in Pharo 9
- [ x ] refactoring works 
- [ x ] has its own refactoring class  
- [ x ] has tests before the revision
- [ x ] has command in menu

## Analysis

- [ x ] test checked all pass
- [  ] tests were added
- [  ] tests were refactored
- [ ] implementation reviewed
- [ ] interaction flow todo
