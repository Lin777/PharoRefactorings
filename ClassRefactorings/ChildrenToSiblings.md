# Children to siblings Refactoring

I am a refactoring operation for removing of usages of a deprecated class, that was renamed to I am a refactoring operation for moving a class and its subclasses to a new super class.

You can choose which of the original childclasses should become now siblings.

For example,  we can generate a new Superclass for ClassS in
Object >> ClassP >> ClassS
Object >> ClassP >> ClassS >> ClassC1
Object >> ClassP >> ClassS >> ClassC2
Object >> ClassP >> ClassS >> ClassC3

and choose to move ClassC2 and ClassC3 to the new superclass - ClassNewP.

Object >> ClassP >> ClassNewP >> ClassS
Object >> ClassP >> ClassNewP >> ClassS >> ClassC1
Object >> ClassP >> ClassNewP >> ClassC2
Object >> ClassP >> ClassNewP >> ClassC3

Any method and instance variables,  defined in ClassS and used by the new siblings of ClassS are pushed up to the new superclass.

## Properties

- **Class:** ```RBChildrenToSiblingsRefactoring```
- **TestClass:** ```RBChildrenToSiblingsTest```
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
- [ x ] implementation reviewed
- [ ] interaction flow todo
