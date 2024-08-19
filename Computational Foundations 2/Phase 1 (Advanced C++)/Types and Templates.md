### The auto keyword
The `auto` keyword in C++ allows the compiler to automatically deduce and specify the type of a variable based on its initializer expression. Key use cases include:

1. **Type Deduction**: Automatically infer the type of a variable, especially for complex types like iterators or function return types.
2. **Range-Based for Loops**: Simplify the declaration of loop variables.
3. **Function Return Type Deduction**: Allow the compiler to deduce the return type based on the function's implementation.
4. **Lambda Expressions**: Simplify the syntax for lambda function parameter declarations.

Using `auto` can make code more concise and maintainable, but it's important to ensure the deduced type aligns with the intended usage.

--- 
### Templates
Templates are useful for:
- blueprinting methods which can be overloaded with different data types
- Accepting types as parameters for classes or functions
- conduct generic programming in C++

*Templates are evaluated at compile-time, not runtime!*
-> This makes complex code faster

Defining a function Template:
`template <typename T>`
`T functionName(T parameter1, T parameter2, ...)`
`{`
`// code`
`}`

Calling a Function Template:
`functionName<dataType>(parameter1, parameter2,...);`

C++ Identities that define one of the following:
- A family of classes
- A family of functions
- An alias to a family of types
- A family of variables
- A concept