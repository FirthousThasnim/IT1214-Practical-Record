Session 03 – Using Packages and Handling Same Class Names
Student: 2022/ICT/102 FIRTHOUS S.T
Submitted on: Thursday, 15 May 2025, 11:55 PM

Objectives:
To understand how to:

Use packages in Java.

Access classes with the same name from different packages.

Theory/Concept:
A package in Java is a way to group related classes.

Two or more classes can have the same name if they are in different packages.

These classes can be accessed using:

import statements, or

fully qualified names (e.g., a.Test, b.Test).

Packages help organize code and prevent class name conflicts.

Algorithm:
Create two packages: a and b.

In each package, create a class named Test with a display() method that prints a unique message.

Create a class App in the default package.

In App, use fully qualified names to access both a.Test and b.Test.

Create objects from both classes and call the display() method.

Source Code:
https://github.com/FirthousThasnim/IT1214-Practical-Record/tree/main/Session_03


Sample Output:
Command:
java App
Expected Output:

Hi from class Test in package a  
Hi from class Test in package a  
Hi from class Test in package b
Compilation:
The program was successfully compiled using:

bash
Copy code
javac App.java a/Test.java b/Test.java
Observation:
Both Test classes (from a and b) were successfully accessed and executed.

Fully qualified class names resolved any name conflicts.

Conclusion:
This session demonstrated:

How to create and use Java packages.

How to handle class name conflicts using fully qualified names.

The use of packages to organize code and maintain modularity in Java projects.

