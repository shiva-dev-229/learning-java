# Learning Java

> My hands-on projects from learning Java — a progression from the language basics through the core of **object-oriented programming**: classes, inheritance, composition, and polymorphism, capped with multi-class coding challenges. A learning repository built while working through **Tim Buchalka's "Java Programming Masterclass."**

---

## About

This repo collects the practice projects I built while learning Java in depth. Each concept lives in its own self-contained project, building up from simple programs to the object-oriented principles that the language is built around. Together they trace the path from "first Java program" to designing small systems of cooperating classes.

The work follows **Tim Buchalka's "Java Programming Masterclass"** — full credit to him for the exercises and challenge concepts. This repository is my own implementation of that coursework as a way to learn the language.

---

## Topics covered

| Folder | Concept |
| --- | --- |
| `LearningSimpleJava/` | Java basics and program structure |
| `Classes/` | Defining classes, fields, methods, and objects |
| `Array/` · `Lists/` | Arrays and Java's built-in list collections |
| `ArraysJavaInbuiltListsAutoboxingUnboxing/` | Collections together with autoboxing/unboxing |
| `AutoboxingAndUnboxing/` | Converting between primitives and their wrapper classes |
| `LearningOOPSPartOne/` | First principles of object-oriented programming |
| `Composition/` | Building complex objects from simpler ones ("has-a" relationships) |
| `Inheritance/` | Extending classes and reusing behavior ("is-a" relationships) |
| `Polymorphism/` | One interface, many implementations |
| `OopChallenge/` · `FinaleBurgerChallenge/` | Capstone challenges combining the OOP concepts |

---

## Running the code

Each folder is a standalone IntelliJ IDEA project. To run a project's `Main`, either open the folder in IntelliJ and run it, or compile the sources directly with the JDK:

```bash
# from inside a project's src directory
javac com/**/Main.java
java com.<package>.Main
```

Requires a JDK (Java 8 or newer).

---

## Credit

All exercises and challenge concepts are from Tim Buchalka's "Java Programming Masterclass." This repository is my personal coursework — my hands-on implementation of the material while learning Java's object-oriented foundations.
