# Inline All Senders Refactoring

I am a refactoring for inlining code of this method.

The call to this method in all other methods of this class is replaced by its implementation. The method itself will be removed.

For example, a method
```
foo
 ^ 'text'.
```
is called in
```
baz
 | a |
 a := self foo.
 ^ self foo.
```
inlining in all senders replaces the call to method foo, with its code:
```
baz
 | a |
 a := 'text'.
 ^ 'text'.
```
## Properties

- **Class:** ```RBInlineAllSendersRefactoring```
- **TestClass:** ```RBInlineAllMethodTest```
- **Access to command:** 
    - select method >> open menu >> select "refactorings" option >> select "inline senders" option 
- [ x ] refactoring exist in Pharo 9
- [ x ] refactoring works 
- [ x ] has its own refactoring class  
- [ x ] has tests before the revision
- [ x ] has command in menu

## Analysis

- [ x ] test checked all pass
- [ x ] tests were added
- [ ] tests were refactored
- [ ] implementation reviewed
- [ ] interaction flow todo

## Notes

- Need add tests
