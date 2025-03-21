# Basics of Arrays in Java

## What is an Array?
An **array** is a collection of elements of the same type stored in contiguous memory locations. In Java, arrays are **objects** that can hold multiple values of the same type.

---

## Declaring an Array
Arrays in Java are declared using the following syntax:

```java
// Declaration of an array
int[] numbers; // Preferred way
String[] names;

// Alternative declaration
int numbers[];
String names[];
```

---

## Initializing an Array
An array must be initialized before use. There are three common ways to initialize an array:

1. **Using the `new` keyword**

```java
int[] numbers = new int[5]; // Creates an array of size 5 with default values (0)
```

2. **Declaring and initializing together**

```java
int[] numbers = {10, 20, 30, 40, 50};
String[] names = {"Alice", "Bob", "Charlie"};
```

3. **Using a loop for initialization**

```java
int[] numbers = new int[5];
for (int i = 0; i < numbers.length; i++) {
    numbers[i] = i * 10; // Assigning values
}
```

---

## Accessing Array Elements
Array elements are accessed using **indexing**, starting from `0`.

```java
int[] numbers = {10, 20, 30};
System.out.println(numbers[0]); // Output: 10
System.out.println(numbers[2]); // Output: 30
```

**Note:** Accessing an index out of range (e.g., `numbers[3]` in the above example) will throw an `ArrayIndexOutOfBoundsException`.

---

## Array Length
Each array object has a **length** attribute that stores the number of elements in the array.

```java
int[] numbers = {10, 20, 30, 40, 50};
System.out.println("Array length: " + numbers.length); // Output: 5
```

---

## Looping Through an Array

1. **Using a for loop**

```java
int[] numbers = {10, 20, 30};
for (int i = 0; i < numbers.length; i++) {
    System.out.println(numbers[i]);
}
```

2. **Using an enhanced for loop (for-each loop)**

```java
int[] numbers = {10, 20, 30};
for (int num : numbers) {
    System.out.println(num);
}
```

---

## Summary
- Arrays store multiple values of the same type.
- The index starts at `0`.
- `length` gives the number of elements.
- Use loops to iterate over elements.

This is the very basics of arrays in Java. Happy coding! 🚀
