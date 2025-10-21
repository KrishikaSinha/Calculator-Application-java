# 🧮 Calculator-Application

## 🎯 Project Overview
This project is developed as part of **Java Programming Assignment 2**.  
It demonstrates the concept of **method overloading** in Java by implementing a simple calculator application that performs basic arithmetic operations such as addition, subtraction, multiplication, and division.

---

## 🧩 Features
- ➕ **Addition** — Handles integer and double inputs, including three-integer addition.  
- ➖ **Subtraction** — Subtracts two integers.  
- ✖️ **Multiplication** — Multiplies two double values.  
- ➗ **Division** — Divides two integers safely with divide-by-zero exception handling.  
- 🧠 **Menu-driven Interface** — Interactive console-based user interface.  
- 🧱 **Object-Oriented Design** — Uses separate classes for logic (`Calculator`) and UI (`CalculatorApplication`).

---

## 🛠 Tech Stack

**Language:** Java  
**IDE:** Visual Studio Code *(or any Java IDE like IntelliJ IDEA, Eclipse)*  

### Concepts Used:
- Object-Oriented Programming (OOP)  
- Method Overloading  
- Exception Handling  
- Scanner Class for Input  
- Control Structures *(if, switch, loops)*  

---

## 🧱 Class Structure

### 🔹 `Calculator.java`
Implements all overloaded arithmetic methods:
```java
add(int a, int b)
add(double a, double b)
add(int a, int b, int c)
subtract(int a, int b)
multiply(double a, double b)
divide(int a, int b)
