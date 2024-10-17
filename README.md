Inheritance
Aim
To understand and implement various types of inheritance in C++ .

Theory
Inheritance is a key feature of object-oriented programming (OOP) that allows a new class (derived class) to inherit properties and behaviors (methods) from an existing class (base class). This promotes code reusability and establishes a natural hierarchy between classes.

Key Concepts
Base Class: The class whose properties and methods are inherited.
Derived Class: The class that inherits from the base class.
Access Specifiers: Control the access level of the base class members in the derived class. These include:
public: Members are accessible from outside the class.
protected: Members are accessible within the class and by derived classes.
private: Members are accessible only within the class.
Types of Inheritance
Single Inheritance: A derived class inherits from a single base class.
Multiple Inheritance: A derived class inherits from more than one base class.
Multilevel Inheritance: A class is derived from another derived class.
Hierarchical Inheritance: Multiple classes are derived from a single base class.
Hybrid Inheritance: A combination of two or more types of inheritance.
Algorithm for Inheritance
Single Inheritance:
Start

Initialize the Program

Begin the program by including necessary libraries (e.g., #include <iostream> in C++).
Define Base Class

Define a base class with some properties and methods.
Define Derived Class

Define a derived class that inherits from the base class using the public access specifier.
Main Function

Start the main() function.
Create an object of the derived class.
Access the inherited properties and methods using the derived class object.
End Program

Return 0 to indicate successful execution of the program.
End the main() function.
Multiple Inheritance:
Start

Initialize the Program

Begin the program by including necessary libraries (e.g., #include <iostream> in C++).
Define Base Classes

Define two or more base classes with some properties and methods.
Define Derived Class

Define a derived class that inherits from multiple base classes using the public access specifier.
Main Function

Start the main() function.
Create an object of the derived class.
Access the inherited properties and methods from all base classes using the derived class object.
End Program

Return 0 to indicate successful execution of the program.
End the main() function.
Multilevel Inheritance:
Start

Initialize the Program

Begin the program by including necessary libraries (e.g., #include <iostream> in C++).
Define Base Class

Define a base class with some properties and methods.
Define Intermediate Derived Class

Define a derived class that inherits from the base class using the public access specifier.
Define Final Derived Class

Define another derived class that inherits from the intermediate derived class using the public access specifier.
Main Function

Start the main() function.
Create an object of the final derived class.
Access the inherited properties and methods from all ancestor classes using the final derived class object.
End Program

Return 0 to indicate successful execution of the program.
End the main() function.
Hierarchical Inheritance:
Start

Initialize the Program

Begin the program by including necessary libraries (e.g., #include <iostream> in C++).
Define Base Class

Define a base class with some properties and methods.
Define Multiple Derived Classes

Define multiple derived classes that inherit from the base class using the public access specifier.
Main Function

Start the main() function.
Create objects of each derived class.
Access the inherited properties and methods using the derived class objects.
End Program

Return 0 to indicate successful execution of the program.
End the main() function.
Hybrid Inheritance:
Start

Initialize the Program

Begin the program by including necessary libraries (e.g., #include <iostream> in C++).
Define Base Classes

Define two or more base classes with some properties and methods.
Define Intermediate Derived Class

Define a derived class that inherits from one or more base classes using the public access specifier.
Define Final Derived Class

Define another derived class that inherits from the intermediate derived class and possibly other base classes using the public access specifier.
Main Function

Start the main() function.
Create an object of the final derived class.
Access the inherited properties and methods from all ancestor classes using the final derived class object.
End Program

Return 0 to indicate successful execution of the program.
End the main() function.
