
# Find and Replace Method Refactoring

I am a tool to find occurrences of a method in other methods.

You can select a method and find the occurrences in a search range of your choice, in case of finding occurrences you can change the block containing the occurrence with a call to the selected method.

This refactoring goes hand in hand with RBExtractMethodRefactoring when replacing the code.

## Properties

- **Class:** ```RBFindAndReplaceMethodRefactoring```
- **TestClass:** ```RBFindAndReplaceMethodTest```
- **Access to command:** 
    - select method >> open menu >> select "refactoring" option >> select "find and replace" option
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