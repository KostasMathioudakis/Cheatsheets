# Java cheatseet

## Reserved Java keywords

| Keyword     | Description                                                                                                          |
|-------------|----------------------------------------------------------------------------------------------------------------------|
| boolean     | Used to declare a variable of boolean type, storing True or False values.                                             |
| byte        | Creates a variable for 8-bit data values.                                                                             |
| break       | Ends a loop or switch statement, interrupting the flow under certain circumstances.                                   |
| abstract    | Declares an abstract class.                                                                                           |
| case        | Used with switch statements to mark text blocks.                                                                      |
| try         | Begins a block of code for error checking, followed by catch or finally block.                                        |
| short       | Declares a variable with 16-bit integer capacity.                                                                     |
| void        | Indicates a method has no return value.                                                                               |
| static      | Denotes a class method or class variable.                                                                             |
| synchronized| Used in multithreaded programming to designate critical sections or functions.                                        |
| super       | A reference variable for parent class objects, used to call parent class methods.                                     |
| volatile    | Indicates a variable might change asynchronously.                                                                     |
| while       | Initiates a while loop, repeating a section many times without a predetermined number of iterations.                   |
| catch       | Captures exceptions thrown by try statements, used after the try block.                                               |
| char        | Declares a variable for unsigned 16-bit Unicode characters.                                                           |
| class       | Used to declare a class.                                                                                              |
| continue    | Continues a loop, skipping remaining code under specific circumstances.                                                |
| default     | Defines a default block in a switch statement or as a default access modifier.                                        |
| do          | Declares a loop, repeating a program section multiple times.                                                          |
| double      | Creates a variable for 64-bit floating-point numbers.                                                                 |
| else        | Represents alternate branches in an if statement.                                                                     |
| enum        | Specifies a set of fixed constants.                                                                                   |
| extends     | Shows class inheritance from another class or interface.                                                              |
| final       | Makes variables constant, methods non-overridable, and classes noninheritable.                                        |
| finally     | Code block in try-catch structure, always executed regardless of exceptions.                                          |
| float       | Creates a variable for 32-bit floating-point values.                                                                  |
| for         | Begins a for loop, executing instructions/functions under a condition.                                                |
| if          | Tests a condition, executing the if block if true.                                                                    |
| implements  | Used to implement an interface.                                                                                       |
| import      | Makes classes and interfaces available in the current source code.                                                    |
| throw       | Used to explicitly throw an exception, commonly for custom exceptions.                                                |
| this        | Refers to the current object in a method or constructor.                                                              |
| throws      | Declares an exception, used to propagate checked exceptions.                                                          |
| instanceof  | Checks if an object is an instance of a class or implements an interface.                                             |
| int         | Declares a variable for a signed 32-bit integer.                                                                      |
| interface   | Used to declare an interface.                                                                                        |
| long        | Specifies a variable for a 64-bit integer.                                                                            |
| native      | Indicates a method is implemented in native code using JNI (Java Native Interface).                                   |
| new         | Used to create new objects.                                                                                           |
| null        | Indicates a reference points to nothing.                                                                              |
| private     | An access modifier indicating a method or variable is accessible only within its declaring class.                     |
| protected   | An access modifier allowing access within and outside the package, but through inheritance only.                       |
| public      | An access modifier indicating unrestricted accessibility.                                                            |
| return      | Exits a method upon completion.                                                                                       |

## Primitive Data types

| Data Type | Default Size | Description                                                                                                                                              |
|-----------|--------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| boolean   | 1 bit        | Stores only two values: true and false. Used for simple flags tracking true/false conditions.                                                            |
| char      | 2 bytes      | Represents a single 16-bit Unicode character. Value range from '\u0000' (0) to '\uffff' (65,535).                                                         |
| byte      | 1 byte       | An 8-bit signed two's complement integer with a range from -128 to 127. Used to save memory in large arrays. Default value is 0.                         |
| short     | 2 bytes      | A 16-bit signed two's complement integer with a range from -32,768 to 32,767. Default value is 0.                                                         |
| int       | 4 bytes      | A 32-bit signed two's complement integer with a range from -2^31 to 2^31 - 1.                                                                            |
| long      | 8 bytes      | A 64-bit two's complement integer with a range from -2^63 to 2^63 - 1.                                                                                   |
| float     | 4 bytes      | A 32-bit IEEE 754 floating-point with single precision. Used to save memory in large arrays of floating point numbers.                                   |
| double    | 8 bytes      | A 64-bit IEEE 754 floating-point with double precision. Commonly used for decimal values but not recommended for precise values like currency.            |

## Access modifiers

| Keyword        | Description                                                                                                                                                   |
|----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| static         | Used to denote a class-level variable or method. It belongs to the class rather than instances of the class.                                                  |
| final          | When applied to a variable, it becomes a constant (its value cannot be changed). For methods, it means the method cannot be overridden. For classes, it prevents them from being subclassed. |
| public         | An access modifier that makes the class, method, or variable accessible from any other class.                                                                  |
| private        | An access modifier that restricts the visibility to the same class only. Cannot be accessed from outside the class.                                            |
| protected      | An access modifier that allows visibility within the same package or subclasses in different packages.                                                         |
| default/package-private | If no access modifier is specified, it's the default. Visible to all classes within the same package but not accessible from outside the package.              |
