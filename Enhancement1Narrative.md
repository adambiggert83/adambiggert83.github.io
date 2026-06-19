# Software Design and Engineering Enhancement

## Artifact Description

The artifact selected for this enhancement is a **C++ Course Advising System** originally developed in **CS300: Data Structures and Algorithms**.

The application was designed to:

* Load course information from a CSV file
* Organize course data using an unordered map
* Display a sorted list of courses
* Search for detailed course information
* Display prerequisite relationships

The original application demonstrated foundational computer science concepts including:

* File handling
* Data structures
* Searching and sorting algorithms
* Basic defensive programming

This artifact was originally created as part of a project focused on evaluating efficient data structures for course management.

---

## Justification for Inclusion in the ePortfolio

I selected this artifact because it demonstrates multiple core computer science concepts and provides significant opportunities for enhancement and professional growth.

The original project showcases my ability to:

* Work with structured data
* Implement efficient search functionality
* Develop a command-line application in C++
* Apply data structures to solve real-world problems

### Strengths of the Original Artifact

* Efficient course lookup using an unordered map
* Modular helper functions such as `Split()` and `ToUpper()`
* Basic defensive programming practices
* File validation and invalid-line handling

### Limitations of the Original Artifact

Although the application met the original project requirements, several software engineering limitations were identified:

* All functionality existed in a single source file
* A global unordered map was used for data management
* User interface, file processing, and business logic were tightly coupled
* Limited scalability and maintainability

The enhancement process focused on improving the overall software architecture through modular design and object-oriented programming principles.

---

## Description of Enhancements

Several significant software engineering improvements were implemented during this enhancement.

### Modular Architecture

The application was restructured into multiple source and header files.

The enhanced system now includes dedicated components:

* Course
* CourseManager
* FileLoader
* MenuSystem
* StringUtils

This separation of responsibilities improves organization, maintainability, and future scalability.

### Improved Encapsulation

The `CourseManager` class now manages all course-related operations and encapsulates the unordered map previously stored as a global variable.

Benefits include:

* Improved encapsulation
* Reduced dependencies
* Better maintainability
* Cleaner code structure

### File Processing Separation

The `FileLoader` component isolates CSV processing and file validation from the rest of the application.

This change improves:

* Maintainability
* Reusability
* Testability

### User Interface Improvements

The `MenuSystem` component centralizes menu navigation and user interaction.

This enhancement improves:

* User experience
* Code organization
* Separation of concerns

### Defensive Programming Enhancements

Additional validation and error-handling improvements were implemented, including:

* Invalid menu selection handling
* Malformed course data validation
* Improved error messaging
* Missing prerequisite detection

The enhanced application validates prerequisite references after loading data and warns users when prerequisite courses do not exist in the catalog.

### Advising Summary Feature

A new advising summary feature was implemented to present prerequisite information in a clearer and more user-friendly format.

This enhancement improves academic decision support and advising functionality.

---

## Skills Demonstrated

This enhancement demonstrates proficiency in:

* C++
* Object-Oriented Programming
* Software Architecture
* Encapsulation
* Modular Design
* Separation of Concerns
* Defensive Programming
* Input Validation
* Error Handling
* Maintainable Software Design

---

## Course Outcomes Achieved

### Outcome 1

**Design and evaluate computing solutions that support organizational goals and decision making.**

The advising summary feature improves the presentation of prerequisite information and supports academic planning and decision-making processes.

### Outcome 2

**Develop professional communications appropriate to technical and non-technical audiences.**

This enhancement improved documentation, system organization, and communication of application functionality through clearer structure and design.

### Outcome 3

**Apply algorithmic principles and computer science practices.**

The application continues to utilize efficient data structures while evaluating design trade-offs during the refactoring process.

### Outcome 4

**Apply software engineering practices and technologies to create computing solutions.**

This outcome was strongly demonstrated through:

* Modular architecture
* Encapsulation
* Object-oriented design
* Defensive programming
* Improved maintainability

### Outcome 5

**Develop a security mindset through validation and secure design practices.**

Improved validation and defensive programming techniques help reduce potential input-related errors and improve system reliability.

---

## Reflection on the Enhancement Process

This enhancement reinforced the importance of software engineering principles such as modularity, maintainability, separation of concerns, and defensive programming.

One of the most significant lessons learned was that functionality alone does not guarantee software quality. While the original application worked correctly, its tightly coupled design would have made future maintenance and expansion difficult.

Refactoring the application into multiple components significantly improved readability, maintainability, and scalability.

One challenge involved reorganizing the code without disrupting existing functionality. Separating responsibilities into distinct classes required careful planning to ensure consistent communication between components.

Another challenge involved strengthening validation and error handling while preserving the simplicity of the original user interface.

Overall, this enhancement demonstrates meaningful growth in my understanding of professional software engineering practices and results in a significantly more maintainable, scalable, and professionally designed software solution.

---

## Downloads

* Original Artifact
* Enhanced Artifact
* Enhancement Narrative
