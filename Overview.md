# REFACTORINGS WITH COMMAND

## CLASS
- Rename (Code OK, Test OK, UI OK - Uses UIManager, Show changes NO, Commander1, Shortcut cmd+R, RBRenameClassRefactoring) 
- Remove (Code OK, Test OK, UI OK - Shows some messages of class references and asks if we want remove anyway, Show changes OK, Commander1, Shortcut cmd+X, RBRemoveClassRefactoring) 
- Insert superclass (Code OK, Test OK, UI OK- Uses UIManager, Show changes NO, Commander1, Shortcut NO, RBAddClassRefactoring) 
- Insert subclass (Code OK, Test OK, UI OK- Uses UIManager, Show changes NO, Commander1, Shortcut NO, RBAddClassRefactoring) 
- Generate subclass (New subclass) (Code OK, Test OK, UI OK- Uses UIManager, Show changes NO, Commander1, Shortcut NO, RBAddClassRefactoring) 
- Abstract instance variables (Replaces every direct access to instVar with accessor methods) (Code NotOK, Test OK, UI NO, Show changes OK, Commander1, Shortcut cmd+AA - NotOk, RBAbstractInstanceVariableRefactoring)
- Generate accesors (only for instVars from class menu) (Code OK, Test OK, UI NO, Show changes OK, Commander1, Shortcut cmd+GA, RBCreateAccessorsForVariableRefactoring)
- Protect inst var ---->>> I'm not tested yet
- Pull Up instance/class variable (Code OK, Test OK, UI NO, Show changes OK, Commander1, Shortcut NO, RBPullUpInstanceVariableRefactoring)
- Push down instance/class variable (Code NotOk - work well for instance but not with class vars, Test OK, UI OK shows messages with references to var, Show changes OK, Commander1, Shortcut NO, RBPushDownInstanceVariableRefactoring) 
- Remove keeping subclasses (Code OK, Test OK, UI - show messages of references and remove anyway, Show changes OK, Commander1, Shortcut NotOk, RBRemoveClassKeepingSubclassesRefactoring) 
- Remove instance/class variable (Code OK, Test OK, UI show messages of references, Show changes NO, Commander1, Shortcut cmd+X, RBRemoveInstanceVariableRefactoring) 
- Rename instance/class variable (Code OK, Test OK, UI OK - Uses UIManager and show warnings, Show changes NO, Commander1, Shortcut cmd+R, RBRenameInstanceVariableRefactoring) 

## METHOD
- Add parameter (Code OK, Test OK, UI OK - Uses UIManager, Show changes OK, Commander1, Shortcut NO, RBAddParameterRefactoring)  
- Inline senders (inline target sends) (Code OK, Test OK, UI NO, Show changes OK, Commander1, Shortcut NO, RBInlineAllSendersRefactoring) 
- Move to class/inst side (no swap)(Code NotOK, Test OK - needs more, UI NO, Show changes NO, Commander1, Shortcut cmd+TC, cmd+TI, RBMoveMethodToClassRefactoring) --->> It does not check the references that the method has (this can to broke some moved methods and their references)
- Push Up (Code OK, Test OK, UI OK - shows warnings with references, Show changes OK, Commander1, Shortcut cmd+PU, RBPullUpMethodRefactoring)  
- Push Down (Code OK, Test OK, UI OK, Show changes Ok, Commander1, Shortcut cmd+PD, RBPushDownMethodRefactoring)
- Remove (Code -, Test -, UI Show warning to cancel or procedes, Show changes NO, Commander1, Shortcut cmd+X, ---- )
- Remove parameter (Code OK, Test OK, UI OK - shows warnings to procede, Show changes OK, Commander1, Shortcut NO, RBRemoveParameterRefactoring) 
- Rename (reorder args) (Code OK, Test OK, UI OK, Show changes NO, Commander1, Shortcut cmd+R, RBRenameMethodRefactoring) 
- Find and replace (Code OK, Test OK, UI OK, Show changes NotOK, Commander1, Shortcut NO, RBFindAndReplaceMethodRefactoring) ---> It stills not considering some cases, like send some args, inst vars, etc
- Move method to another class (Code OK, Test OK - needs more, UI OK - shows a selector of class, Show changes NO, Commander1, Shortcut NO, RBMoveMethodToClassRefactoring) -->> does not consider method references to instance variables or other methods of the class
- Remove and the ones in subclasses (Code OK, Test OK, UI OK - shows warnings, Show changes NO, Commander1, Shortcut NO, RBRemoveHierarchyMethodRefactoring) 
- Replace senders (Code OK, Test OK, UI OK - shows warnings, Show changes OK, Commander1, Shortcut NO, RBReplaceMethodRefactoring) --> could improve UI

## SOURCE CODE
- Extract method (Code NotOK, Test OK, UI OK, Show changes NO, Commander1, Shortcut NO, RBExtractMethodRefactoring)
- Extract temp (Code OK, Test OK, UI OK-uses UIManager, Show changes NO, Commander1, Shortcut NO, RBExtractToTemporaryRefactoring)
- Inline method (Code OK, Test OK, UI OK, Show changes NO, Commander1, Shortcut NO, RBInlineMethodRefactoring)
- Inline temporary (Code OK, Test OK, UI OK, Show changes NO, Commander1, Shortcut NO, RBInlineTemporaryRefactoring)
- Move temp to instVar (Code OK, Test OK, UI NO, Show changes NO, Commander1, Shortcut NO, RBTemporaryToInstanceVariableRefactoring)
- Rename argument or temporary (Code OK, Test OK, UI -uses UIManager, Show changes NO, Commander1, Shortcut cmd+R, RBRenameArgumentOrTemporaryRefactoring)

# REFACTORING WHITOUT COMMAND

## CLASS
- Realize (Code NotOK, No test, UI NO, Commander1) 
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
- Package rename should rename the manifest 

