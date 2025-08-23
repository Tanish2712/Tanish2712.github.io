# Java Notes

## Introduction

Java is a high-level, class-based, object-oriented programming language
that is designed to have as few implementation dependencies as possible.

## Features of Java

-   Platform Independent
-   Object-Oriented
-   Simple and Secure
-   Robust and Portable
-   Multithreaded

## Basic Structure of a Java Program

``` java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

## Key Concepts

1.  **Classes and Objects**
    -   Class: Blueprint of objects.
    -   Object: Instance of a class.
2.  **Inheritance**
    -   Mechanism to acquire properties of another class.
3.  **Polymorphism**
    -   Ability to take multiple forms (compile-time and runtime).
4.  **Abstraction**
    -   Hiding implementation details and showing functionality.
5.  **Encapsulation**
    -   Wrapping variables and methods into a single unit (class).

## Commonly Used Data Types

-   int
-   float
-   double
-   char
-   boolean
-   String

## Control Statements

-   if, if-else, nested if
-   switch-case
-   for, while, do-while loops
-   break, continue

## Example: Factorial Program

``` java
import java.util.Scanner;

public class Factorial {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter a number: ");
        int n = sc.nextInt();
        int fact = 1;
        for(int i=1; i<=n; i++) {
            fact *= i;
        }
        System.out.println("Factorial: " + fact);
    }
}
```
