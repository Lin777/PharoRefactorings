# Rename Instance Variable

I am a refactoring for rename instance variables.

I rename the instance variable in the class definition, in all methods refering to this variable and rename the old accessors.

My precondition verifies that the new variable is valid and not yet used in the whole class hierarchy.

## Properties

- **Class:** ```RBRenameInstanceVariableRefactoring```
- **TestClass:** ```RBRenameInstanceVariableTest```
- **Access to command:** 
    - Select instance variable >> cmd + R
    - Select instance variable >> open menu >> select "Rename" option
- [ x ] refactoring exist in Pharo 9
- [ x ] refactoring works 
- [ x ] has its own refactoring class  
- [ x ] has tests before the revision
- [ x ] has command in menu

## Analysis

- [ x ] test checked all pass
- [ ] tests were added
- [ ] tests were refactored
- [ ] implementation reviewed
- [ ] interaction flow todo
