# solid-principles-in-swift
Swift code snippets showing how to use each of the S.O.L.I.D Principles.

**What are the S.O.L.I.D Principles?**

The S.O.L.I.D Principles of Object Orientated Programming were developed by Robert C. Martin (Uncle Bob) in his Design Principles and Design Patterns paper published in 2000.

The 5 parts of S.O.L.I.D refer to;

 - Single Responsibility Principle (SRP)
 - Open/Closed Principle (OCP)
 - Liskov’s Subsititution Principle (LSP)
 - Interface Segregation Principle (ISP)
 - Dependency Inversion Principle (DIP)

These principles provide guidelines to help programmers build a more rubust modular software architecture.

Benefits of using the S.O.L.I.D Principles;

  - Helps avoid building code where making a change in one place breaks the code unexpectedly in others parts.
  - Promotes code reuse.
  - Makes code refactoring easier.
  - Makes writing automated software tests easier.

## Single Responsibility Principle
Every module/class written should have one responsibility and all of the defined module/class's services should be narrowly aligned with that responsibility. This means that every module/class defined within a code base adhering to S.O.L.I.D, should have one and only one reason to change. 

**Benefits of SRP**

Increases code readability (each module/class does only one thing), extensibility, and ease of maintenance.

## Open/Closed Principle
Classes and Modules should be open for extension but closed for modification

**Benefits of OCP**

Code doesnt have to change everytime the requirements change.

## Liskov’s Subsititution Principle
Child classes should never break the parent class type definitions 

It means, we must make sure that new derived classes should extend the base classes without changing the base class behavior

As simple as, a subclass should override the parent class methods in a way that doesnt break the funtionality of base class from client point of view.

**Benefits of OCP**

Similar to OCP code doesnt have to change everytime the requirements change.

## Interface Segregation Principle

Make fine grained interface that are client specific

This principle solves FAT interface problems of Object Oriented Programming

A interface is called FAT when it has too many methods which contains more information than we really want.

**Benefits of ISP**

High cohesion - better understandability, robustness
Low coupling - better maintainability, high resistance to changes

## Dependency Inversion Principle
