### Components
Variables are declared in three components:
1. Types
2. Identifiers
3. Value

### Scopes
There are three types of scopes for variables:

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