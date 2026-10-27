# Java Guitar Inventory System (OOAD Design Pattern)

> **An Object-Oriented Analysis and Design (OOAD) implementation in Java modeling a musical instrument inventory and customer specification search system.**

[![Java](https://img.shields.io/badge/Language-Java-ED8B00?logo=openjdk&logoColor=white)](https://oracle.com/java)
[![OOAD](https://img.shields.io/badge/Pattern-Object--Oriented%20Analysis%20%26%20Design-blue)](https://github.com/keerthi19hub)

---

## 1. Project Overview

The **Guitar Inventory System (GIS)** is an applied implementation of classic Object-Oriented Analysis and Design (OOAD) principles inspired by *Head First Object-Oriented Analysis & Design*.

It models a guitar store's inventory management and search workflow. Instead of performing rigid, brittle string matching, the system separates instrument specifications from inventory storage, allowing customers to query guitars based on builder, model, wood combinations, and price constraints.

---

## 2. Core Classes & Architecture

| Class | Responsibility |
| :--- | :--- |
| `Guitar.java` | Domain entity encapsulating serial number, builder, model, back wood, top wood, and pricing |
| `GuitarInventorySystem.java` | In-memory inventory repository providing instrument registration and matching search algorithms |
| `Main.java` | Application driver initializing inventory catalogs and executing customer query scenarios |

---

## 3. Visual Artifacts
- The repository contains `IMG_20250318_145800.jpg` documenting system design and class notes.

---

## 4. Compilation & Running

```bash
# 1. Clone repository
git clone https://github.com/keerthi19hub/gis-java.git
cd gis-java

# 2. Compile Java classes
javac *.java

# 3. Run application
java Main
```

---

## 5. Author & Context

- **Author:** **Keerthi N** (*Alliance University, BCA*)
- **Subject:** Object-Oriented Analysis and Design (OOAD)
- **Verified Contribution:** Authored domain entity definitions, inventory indexing, and search matching algorithms.

---

## 6. License

Released under the [MIT License](https://opensource.org/licenses/MIT).
