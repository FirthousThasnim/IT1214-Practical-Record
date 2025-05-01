# Practical 01 – Introduction to Java Programming  
**Date:** 26.03.2025  
**Student:** 2022/ICT/102 FIRTHOUS S.T  
**Submitted on:** Friday, 25 April 2025, 12:28 AM

---

##  Program 1: MySecondClass

###  Objectives:
To learn how to pass and use command-line arguments in Java.

###  Theory/Concept:
Command-line arguments allow users to send input values while starting the Java program.  
These values are stored in the `args` array of the `main` method.

###  Algorithm:
1. Create a class `MySecondClass` with a `main` method.
2. Access values from `args[0]`, `args[1]`, and `args[2]`.
3. Print each argument.
4. Print extra messages if needed.

###  Source Code:
[View on GitHub](https://github.com/FirthousThasnim/IT1214-Practical-Record/tree/main/Session_01/Lession_01)

###  Sample Input & Output:
**Command:**
```bash
java MySecondClass zero one two Hi Ann
```
**Output:**
```
The first argument is zero  
The second argument is one  
The third argument is two  
Hi Ann
```

###  Observation:
The program successfully printed each command-line argument passed while running.

###  Conclusion:
Command-line arguments can be accessed in Java programs easily using the `args` array.

---

##  Program 2: App and P3.java

###  Objectives:
To understand how multiple classes interact and call methods from each other.

###  Theory/Concept:
In Java, one class can create objects of another class and call its methods.  
We can group different functionalities into separate classes.

###  Algorithm:
1. Create two classes (e.g., `ClassOne` and `ClassTwo`).
2. Write a method inside each class to print some values.
3. Create a third class `App` that creates objects of both classes and calls their methods.
4. Compile all classes and run `App`.

###  Source Code:
[View on GitHub](https://github.com/FirthousThasnim/IT1214-Practical-Record/tree/main/Session_01/Lession_02)

###  Sample Input & Output:
**Command:**
```bash
java App
```
**Output:**
```
From Class One a =10  
From Class Two a =10  
From Class Two a =20  
From Class Two a =30
```

###  Observation:
The `App` class could access methods from both `ClassOne` and `ClassTwo` successfully.

###  Conclusion:
Java allows creating objects from other classes to organize and reuse code easily.

---

##  Program 3: MyFirstClass

###  Objectives:
To practice basic output in Java and printing on the same line and new line.

###  Theory/Concept:
- `print()` displays text on the same line.  
- `println()` displays text and moves to the next line.

###  Algorithm:
1. Create a class `MyFirstClass` with a `main` method.
2. Use `System.out.print()` for same-line text.
3. Use `System.out.println()` for next-line text.

###  Source Code:
[View on GitHub](https://github.com/FirthousThasnim/IT1214-Practical-Record/tree/main/Session_01/Lession_03)

###  Sample Input & Output:
**Command:**
```bash
java MyFirstClass
```
**Output:**
```
This is IT2141 Practical session 1This prints next in a new line  
This is a new line
```

###  Observation:
The program correctly printed text first on the same line and then in a new line.

###  Conclusion:
Using `print()` and `println()`, we can control how text is shown in Java programs.
