# Squarelotron (Java)

A Java implementation of the **Squarelotron puzzle game**, which applies transformations (flips, rotations, inversions) on square matrices of various sizes.

---

## Project Explanation
The Squarelotron is a matrix-based puzzle game where an `N x N` grid undergoes various transformations.  
This project demonstrates **object-oriented programming, inheritance, and method overriding** through multiple implementations.

### Core Components
- **Squarelotron (Abstract Base Class)**  
  - Defines the structure and rules of the puzzle.  
- **SmallSquarelotron & LargeSquarelotron**  
  - Specializations for different grid sizes (e.g., 4x4, 5x5).  
- **SquarelotronMethods**  
  - Implements transformations such as flips, inversions, and rotations.  
- **Factory Classes (CreateSquarelotron, etc.)**  
  - Allow dynamic creation of puzzle instances.  
- **Tests (SqurelotronTest, MainTestClass)**  
  - Validate correct functionality of transformations.

---

## Repository Structure
Squarelotron/
┣ src/
┃ ┣ Squarelotron.java
┃ ┣ SquarelotronMethods.java
┃ ┣ SmallSquarelotron.java
┃ ┣ LargeSquarelotron.java
┃ ┣ CreateSquarelotron.java
┃ ┣ CreateSmallSquarelotron.java
┃ ┣ CreateLargeSquarelotron.java
┃ ┣ SqurelotronTest.java
┃ ┗ MainTestClass.java
┣ 📄 LICENSE
┣ 📄 README.md

---

## Features
- Create squarelotron boards of different sizes
- Apply transformations:
  - Upside-down flip
  - Left-right flip
  - Inverse flip
  - Rotate right/left
- Extensible class design using inheritance
- Includes automated tests for validation

---

## Technologies
- Language: Java
- Paradigm: Object-Oriented Programming (Inheritance, Polymorphism)
- Tools: Any Java IDE (Eclipse, IntelliJ IDEA, VS Code)

--- 

## Author
- Developed by Nicolas Constantinou
- 2025

---

## 🚀 Usage

### Compile/Run:
```bash
javac src/*.java -d bin
java -cp bin MainTestClass
