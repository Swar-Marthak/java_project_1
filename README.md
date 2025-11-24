# Campus Course & Records Manager (CCRM)

## Overview

Campus Course & Records Manager (CCRM) is a Java console-based application designed for educational institutions to manage student data, courses, enrollments, and grading.

It demonstrates advanced Java concepts such as Object-Oriented Programming (OOP), design patterns, use of modern Java features (Streams, Lambda Expressions, NIO.2), and effective software design best practices.

---

## Features

- **Student Management:** Create, update, list, and manage students with validation and status handling.
- **Course Management:** Build and administer courses with flexible criteria and instructor assignments.
- **Enrollment & Grading:** Enroll students, record grades, calculate GPA, and generate transcripts.
- **File I/O:** Import/export CSV and JSON data; backup and restore data with timestamps.
- **Reporting:** Generate statistics such as GPA distributions and top-performing students.
- **Utility Modules:** Showcases algorithms using recursion, sorting, and validation utilities.

---

## Technical Details

- **Core Java:** Classes, Enums, Interfaces, Nested Classes, Collections, Streams API.
- **Design Patterns:** Singleton (Config management), Builder (Course creation), Service Layer.
- **Exception Handling:** Custom exceptions provide robust error management.
- **Modern Features:** Lamdas, functional interfaces, NIO.2 API for file operations.
- **Unit Tests:** (Optional) Test core classes and logic with JUnit or similar.

---

## Project Structure

CampusCourseRecordsManager/
â”œâ”€â”€ src/
â”‚ â””â”€â”€ edu/
â”‚ â””â”€â”€ ccrm/
â”‚ â”œâ”€â”€ Main.java # Application entry point
â”‚ â”œâ”€â”€ cli/ # CLI interface files
â”‚ â”œâ”€â”€ config/ # Configuration classes (Singleton)
â”‚ â”œâ”€â”€ domain/ # Java Beans & Domain Entities
â”‚ â”œâ”€â”€ exceptions/ # Custom exceptions
â”‚ â”œâ”€â”€ io/ # Import/Export and Backup services
â”‚ â”œâ”€â”€ service/ # Business logic and services
â”‚ â””â”€â”€ util/ # Utility and helper classes
â”œâ”€â”€ README.md


---

## Requirements

- Java JDK 11 or higher
- Git for version control
- IDE (VS Code, IntelliJ IDEA, Eclipse) or command line

---

## Usage

1. **Compile:**
    ```
    cd src
    javac edu/ccrm/Main.java
    ```

2. **Run:**
    ```
    java edu.ccrm.Main
    ```

3. Alternatively, use IDE run configurations to compile and run the `Main` class.

---

## Getting Started with VS Code

- Open the project folder.
- Navigate to `src/edu/ccrm/Main.java`.
- Use the VS Code "Run" button or the integrated terminal to build and run.

---


# java_project_1
