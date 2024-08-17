##### Task 1: Compilation & Linking
1. C++ source-code -> compiling
2. Object code & libraries -> linking
3. Executable

1. The source and header files go into the *preprocessor*
2. The preprocessor merges these and creates *extended source files*
3. The compiler makes the source files machine-readable, but keeps name references
4. The linker creates the finished machine code

##### Task 2: Expressions and Operations
Variables are declared in three components:
1. Types
2. Identifiers
3. Value

##### Task 3: Scopes
There are three types of scopes:

*Global Scope*:
- Variable defined outside of any scope
- Available to all other functions within the same file
- Should be avoided

*Local Variable*:
- Defined withing a scope, usually {}
- Will be re-created with every call of that scope

*Local Statics*:
- Availability like a local variable
	- Will __not__ be re-created
