# Java Basics Simplified

## 1. What is Java?
Java is a popular programming language used for building applications. It's known for being **platform-independent**, meaning it can run on different devices without needing to be rewritten. This is because Java code is compiled into bytecode, which can run on any machine that has the Java Virtual Machine (JVM).

## 2. Basic Structure of a Java Program
A basic Java program consists of:
- **Classes**: Blueprints for objects.
- **Methods**: Blocks of code that perform actions.
- **Statements**: Instructions that the program follows.

Here’s a simple Java program:

```
public class HelloWorld {  
    public static void main(String[] args) {  
        System.out.println("Hello, World!");  
    }  
}  
```

## 3. Key Components

- **Class**: Every Java program has at least one class (in this case, `HelloWorld`).
- **Method**: `main` is the entry point of a Java program. It’s where the program starts executing.
- **Statements**: `System.out.println("Hello, World!");` prints the message to the screen.

## 4. Variables
Variables are used to store data. They have a type and a name. For example:

```
int age = 25;  // an integer variable  
String name = "Alice";  // a string variable  
```

## 5. Data Types
Java has several data types:
- **Primitive Types**: `int`, `float`, `double`, `boolean`, etc.
- **Reference Types**: `String`, arrays, objects, etc.

## 6. Operators
Operators perform operations on variables and values:
- **Arithmetic Operators**: `+`, `-`, `*`, `/`, `%`
- **Comparison Operators**: `==`, `!=`, `>`, `<`, `>=`, `<=`
- **Logical Operators**: `&&` (AND), `||` (OR), `!` (NOT)

## 7. Control Flow Statements
- **If-Else**: Used to make decisions.

```
if (age > 18) {  
    System.out.println("Adult");  
} else {  
    System.out.println("Minor");  
}  
```

- **Loops**: Repeating code until a condition is met.  
  - **For Loop**: Repeats for a specific number of times.

```
for (int i = 0; i < 5; i++) {  
    System.out.println(i);  
}  
```

  - **While Loop**: Repeats as long as a condition is true.

```
int i = 0;  
while (i < 5) {  
    System.out.println(i);  
    i++;  
}  
```

## 8. Arrays
An array is a collection of elements (all of the same type). Example:

```
int[] numbers = {1, 2, 3, 4, 5};  
System.out.println(numbers[0]);  // Outputs 1  
```

## 9. Methods
Methods are reusable blocks of code that perform specific tasks. Here’s an example:

```
public class Example {  
    public static void greet(String name) {  
        System.out.println("Hello, " + name);  
    }  

    public static void main(String[] args) {  
        greet("Alice");  // Calls the greet method  
    }  
}  
```

## 10. Object-Oriented Programming (OOP)
Java is an **object-oriented** language, meaning it focuses on objects and classes. The four main principles of OOP are:

- **Encapsulation**: Hiding the internal workings of an object and exposing only what’s necessary.
- **Inheritance**: One class can inherit properties and methods from another.
- **Polymorphism**: A method can behave differently depending on the object it is acting on.
- **Abstraction**: Hiding complex implementation details and showing only essential features.

Example of a class with properties and methods:

```
public class Car {  
    String make;  
    String model;  
    
    public void start() {  
        System.out.println("The car is starting");  
    }  
}  
```

## 11. Access Modifiers
Java uses access modifiers to control access to classes, methods, and variables:
- `public`: Accessible from anywhere.
- `private`: Accessible only within the same class.
- `protected`: Accessible within the same package and by subclasses.
- `default` (no modifier): Accessible only within the same package.

## Summary
- **Class**: Blueprint of objects.
- **Method**: Block of code that performs actions.
- **Variables**: Store data (int, String, etc.).
- **Control Flow**: Decisions (if-else), loops (for, while).
- **Arrays**: Store multiple values of the same type.
- **OOP**: Organize code using objects and classes.
