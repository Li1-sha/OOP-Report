# Object-Oriented Programming (OOP) report 
## By Shahad Al Harthy

---

### Introduction
Object-oriented Programming (OOP) is a model based on the concept of "objects", which combine data and behavior (attributes & methods). OOP is a median to many modern programming languages, including Java, Python and C++. Its approach models real-world things, simplifying design and assisting with strong software development.

---

### Structure of OOP
- **Class**: User-defined data types that act as an outline for individual objects, attributes and methods.
- **Object**: Instance of a class, corresponds to real-world entities.
- **Attribute**: Variable representing object state - features that distinguish classes.
- **Method**: Functions that objects perform, defined inside a class.

---

### Core Principles of OOP
1. **Encapsulation**: Hiding internal state and behavior while exposing a clean interface. Other objects do not have access to it or be able to make changes.
    - Provides program security and control over object state changes; therefore make sthe program more understandable and reduces risk of errors .
2. **Abstraction**: Simplifying complexity by exposing only relevant details. Allows the construction of more comprehensible programs.
    - The code inside becomes largely independent of other objects.
3. **Inheritance**: Enabling a new (child) class to acquire properties and behaviors of an existing (parent) class. Has the option to override and augument properties and methods.
    - Prevents duplicaton of code and simplifies maintainance. It also eliminates the need to create new classes for objects used in the program.
4. **Polymorphism**: Complements inheritance by allowing objects of different classes to be treated uniformly. Helps create more flexible and modular programs.
    - Simplifies the development process by allowing the use of common methods and functions for multiple objects.

---

### Advantages of OOP
- **Modularity**: Code organized into classes, easier to manage.
- **Reusability**: Common features can be inherited.
- **Maintainability**: Easier updates and modifications.
- **Data Security**: Restrict unauthorized access using encapsulation.

---

### Example (Java)
```java
// Base class 'Vehicle'
class Vehicle {
    // Attribute:
    String brand = "Generic";

    // Method:
    void honk() {
        System.out.println("Beep!");
    }
}
// Subclass 'Car' inherits from 'Vehicle'
class Car extends Vehicle {
    // Additional Attribute
    String model = "Sedan";
}
// Main class to run program
public class Main {
    public static void main(String[] args) {
        // Instance of car created
        Car myCar = new Car();
        // Call honk() method inherited from 'Vehicle'
        myCar.honk();
        // Print brand & model of the car
        System.out.println(myCar.brand + " " + myCar.model);
    }
}
```

---

### References
https://www.techtarget.com/searchapparchitecture/definition/object-oriented-programming-OOP 

https://career.softserveinc.com/en-us/stories/what-is-object-oriented-programming-oop-explaining-four-major-principles 

https://www.geeksforgeeks.org/cpp/benefits-advantages-of-oop/ 
