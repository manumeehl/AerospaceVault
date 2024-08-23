### The principles of Object Orientation

__Encapsulation__
Encapsulation is a mechanism hiding data and their internal representation from the outside world. Data is accessed only through accessor methods. In C++ Object Orientation, this is supported by the keywords private, protected, and public.

__Abstraction__
The object-oriented design is a semantic abstraction of the underlying thing and does not follow or imply implementation logic. A user should not know the implementation, but only the interface (e.g., a documented the header file) to use the implementation. Facilitates re-use and drop-in replacements, e.g., with more efficient algorithms.

__Inheritance__
The semantic “is-a” relationship is used to model software from simple to complex. Implementing the least complex object and specializing it with more specific versions is done through inheritance. Multiple inheritance is possible in C++. Type Casting implements an important feature of inheritance to generalize complex objects to instances of a parent class.

__[[Polymorphism]]__
Each class can implement each method in a different way. Which method is chosen is based on the method being virtual. Typically, the method is taken from the type of the object at the moment of invocation. But for virtual methods, the method of the type at instantiation is being used. In this way, multiple classes of the same type can have a different behavior for the same method

---
##### Class Relationships

- *Association*: Reference to one other object
- eg. Bank Account, Customer
- *Dependency*: Issues a call to a member object
- eg. Student, Text Book
- *Inheritance*: Class derived from another class
- eg. Car, Sedan

Specific Cases of Association:
 - *Aggregation*: Child can exist independently
	 - eg. Class, Students
- *Composition*: Childs cannot exist independently
- eg. House, Room

---

### Generic programming
"Writing code that works with a variety of types presented as arguments as long as those argument types meet specific syntactic and semantic requirements"

##### Priority of functions
1. How well do the parameter [[Types]] match? -> Best match of evaluated type conversion losses
2. Evaluation of return types similar to 1
3. None-templated functions are preferred over templated ones.
4. The more specialized function is chosen.

##### Structs
"User-define composite data structures"
- Handy to organize data
- Grouping of multiple members with different data types