##### Namespaces
- A declarative region that provides a scope to the identifiers inside it
- An organizational element to group your code into logical units
- Custom namespaces can be created like this:

	namespace Example
	{
		class ObjectManager {
			public: void DoSomething() {}
		};
		void Func(ObjectManager) {}
	}

##### The include-statement
- Tells the pre-processor to include the contents of a specific file at the point where the directive appears
- Helps to modularize the code and reusing functionalities from other files and libraries

##### Templates
*Templates are evaluated at compile-time, not runtime!*

C++ Identities that define one of the following:
- A family of classes
- A family of functions
- An alias to a family of types
- A family of variables
- A concept

Templates are useful for:
- blueprinting methods which can be overloaded
- accepting types as parameters for classes or functions
- conduct generic programming in C++


##### Generic programming
"Writing code that works with a variety of types presented as arguments as long as those argument types meet specific syntatic and semantic requirements"

##### Priority of functions
1. How well do the parameter types match? -> Best match of evaluated type conversion losses
2. Evaluation of return types similar to 1
3. None-templated functions are preferred over templated ones.
4. The more specialized function is chosen.

##### Structs
"User-define composite data structures"
- Handy to organize data
- Grouping of multiple members with different data types
- 
