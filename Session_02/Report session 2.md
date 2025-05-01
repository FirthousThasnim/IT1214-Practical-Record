Here's your content neatly formatted in **Markdown** for GitHub documentation—perfect for a `README.md` or notes file in your repo:

---

# Practical 02 – Using Packages and Multiple Classes  
**Student:** 2022/ICT/102 FIRTHOUS S.T  
**Submitted on:** Thursday, 01 May 2025, 7:20 AM  

---

## 🎯 Objectives:
To understand how to use Java packages and access classes from different packages using `import`.

---

## 📚 Theory/Concept:
- Packages in Java are used to group related classes.
- You can access classes from other packages using:  
  ```java
  import packageName.ClassName;
  ```
- This helps organize large Java projects and avoids class name conflicts.
- Classes from different packages can be compiled and executed together.

---

## 🧠 Algorithm:
1. Create separate packages like `p1`, `p2`, and `p1.p3`.
2. Write one class in each package with a method printing a message.
3. In the `App.java` (main class), import these classes.
4. Create objects of those classes and call their methods.
5. Compile all `.java` files together.
6. Run the `App` class.

---

## 💻 Source Code:
[View on GitHub](https://github.com/FirthousThasnim/IT1214-Practical-Record/tree/main/Session_02)

---

## 🔢 Sample Output:
(No input required from the user)

**Expected Output:**
```
Hi from MyClass in package p1  
Hi from Class2 in package p2  
Hi from Class3 in package p2  
Hi from Class4 in package p1.p3
```

---

## 🔍 Observation:
- Classes from different packages compiled and ran successfully.
- `import` statements allowed access to classes from other packages.
- Java's package structure helped organize the code effectively.

---

## ✅ Conclusion:
Using packages in Java improves project structure and modularity.  
This practical demonstrated how to:
- Create multiple packages,
- Use `import` to access external classes,
- And run a multi-package project successfully.

---

Let me know if you'd like a combined file of all practicals or a visual package structure diagram!
