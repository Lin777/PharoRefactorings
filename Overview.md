# REFACTORINGS WITH COMMAND

## CLASS
- Rename (Code ok, Test ok, UI ok, Commander1) 
- Remove
- Insert superclass
- Insert subclass
- Generate subclass (New subclass)
- Abstract instance variables (Replacing every direct access to  instance  variables with accessor methods)
- Generate accesors (instar, classVar)
- Protect inst var
- Pull Up instance variable
- Pull Up class variable
- Push down instance variable
- Push Down class variable
- Remove keeping subclasses
- Remove instance variable
- Rename class variable
- Rename instance variable

## METHOD
- Add parameter
- Inline senders (inline target sends)
- Move to class side / to inst side (no swap)
- Push Up
- Push Down
- Remove
- Remove parameter
- Rename (reorder args)
- Find and replace
- Move method to class
- Remove and the ones in subclasses
- Replace senders

## SOURCE CODE
- Extract method
- Extract temp
- Inline method
- Inline temporary
- Move temo to instVar
- Rename argument or temporary

# REFACTORING WHITOUT COMMAND

## CLASS
- Realize (Does not work)
- Split
- Add class variable
- Add instance variable
- Deprecated
- Move a class and its subclass to a new superclass
- Rename with regexp

## METHOD
- Deprecated
- Inline parameter
- Move method to instVar (RBMoveMethodRefactoring)

## SOURCE CODE
- Extract method (but you can choose to which component (instance or argument variable) the new method is added)
- Move variable definition to Block or Scope
- Split cascade

## VARIABLE
- Replacing every direct access to  class variables with accessor methods 

## PACKAGE
- Package rename


