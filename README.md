# README.md

Malcolm Cajuste Notes
HeadFirst Java

"Chapter 9"

- Instance variables are declared inside a class not a method..
- Local varbiales are inside a method..
- When you call a method the method lands on the top of a call stack..
- If the local variable is a reference to an object, only the variable goes on the stack..
- Instance variables do have a default value. 0 or 0.0 for numeric primitives, false for booleans and null for references.
- If you write a constructor that takes arguments, and still want a no-arg constructor, you'll have to build the no-arg constructor yourself.
- If you have more than one constructor in a class, the constructors MUST have a different arguements lists.
- Overloaded constructors means you have more than one constructor in your class
- The default is always a no-arg constructor.
- A constructor is the code that runs when you say new on a class type.



"Chapter 10"


- A static method means "behvaior not dependent on a instance variable, so no instance/object is required.
- Static variables are shared
- All instances of the same class share a single copy of the static variables
- All static variables in a class are initialized before any object of that class can be created
- A static intiliazer is a block of code that runs when a class is loaded, before any other code can use the class, so it's a great place to initiliaze a stati final variable 
