
Used in the context of inheritance and [[Polymorphism]] to allow derived [[Classes and Structs|Classes]] to override the behavior of the base class function. 

### Purposes 
- Interface definition: communicate in the interface definition in header file that this function is intended to be overriden. 
- Polymorphism: Virtual functions enable polymorphism, allowing objects of derived classes to be treated as objects of the base class while still calling the correct derived class method at runtime. 
- Code Seperation: Declaring virtual functions in the header file maintains separation between declarations in header (.h) and implementations in source file (.cpp).
- • Compiler Requirements: To allow proper vtable construction.