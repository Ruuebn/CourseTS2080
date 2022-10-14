### Interface classes

Interface class
    - Acts as a blueprint for designing classes
        - Used by multiple classes -> classes uses methods from interfaces
    - Can only contain method declarations, no variables
    - Implement all the methods in the class that extends the interface
        - Usually used when you want to share the same methods with different classes
    - Denoted by a dotted line (A ---------- B: A uses interface B)
        - Can use arrows
    - Many interfaces can be implemented in a class, but a class can only inherit from one abstract class
    - You cannot override interface methods, interface methods must then already be implemented within the interface class
    
Enumeration
    - contain sets of named identifiers that represent the values of the enumeration
        - i.e weekdays (monday, tuesday, wednesday, ...)
DataTypes
    - DataTypes do not have methods, only variables
    - DataTypes abstract a set of primitive types like integers, strings, etc
