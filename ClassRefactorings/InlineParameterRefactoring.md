# Inline Parameter Refactoring

I am a refactoring for removing and inlining method arguments.

If all callers of a method with arguments, call that method with the same literal argument expression, you can
remove that argument and inline the literal into that method.

My precondition verifies that the method name without that argument isn't already used and that all callers
supplied the same literal expression.

For example, a method foo: anArg
```
foo: anArg
 anArg doSomething.
```
and all senders supply the same argument:
```
method1
 anObject foo: 'text'.

method2
 anObject foo: 'text'.
```
the method argument can be inlined:
```
foo
 | anArg |
 anArg := 'text'.
 anArg doSomething.
```
and the callers just call the method without any arguments:
```
method1
 anObject foo.
```
## Properties

- **Class:** ```RBInlineParameterRefactoring```
- **TestClass:** ```RBInlineParameterTest```
- **Access to command:** ???
- [x] refactoring exist in Pharo 9
- [x] refactoring works 
- [x] has its own refactoring class  
- [x] has tests before the revision
- [ ] has command in menu

## Analysis

- [x] test checked all pass
- [ ] tests were added
- [ ] tests were refactored
- [ ] implementation reviewed
- [ ] interaction flow todo

## Notes

- Need add tests
