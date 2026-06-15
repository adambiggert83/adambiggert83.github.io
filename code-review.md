# Code Review

## Video Presentation

🎥 **Watch the Full Code Review**

[View Code Review Video on YouTube](https://youtu.be/BfGHS7dqpaw)


## Overview

The purpose of this code review was to evaluate the original artifact selected for my CS 499 Computer Science Capstone project and identify opportunities for enhancement across three computer science categories:

* Software Design and Engineering
* Algorithms and Data Structures
* Databases

This review served as the foundation for the enhancement plan implemented throughout the capstone experience and demonstrates my ability to evaluate existing software, identify areas for improvement, and apply professional software development practices.


## Original Artifact

### Course Advising System

**Course:** CS300 – Data Structures and Algorithms

The original artifact was a Course Advising System developed in C++. The application loads course information from a CSV file, stores the data using an unordered map, and allows users to display a sorted course list and view detailed course information, including prerequisites.

### Original Features

* Load course data from a CSV file
* Store course information using an unordered map
* Display all available courses
* Search for individual courses
* Display prerequisite information
* Menu-driven user interface

While the original project successfully met the requirements of the CS300 course, the code review identified several opportunities to improve maintainability, scalability, functionality, and data management.


## Software Design and Engineering Analysis

### Strengths

The original application demonstrated several software engineering strengths:

* Functional and reliable implementation
* Efficient use of data structures
* Clear menu-driven interaction
* Basic validation and file handling
* Logical organization of core functionality

### Areas for Improvement

The review identified several opportunities for enhancement:

* All functionality existed within a single source file
* Use of a global unordered map
* Limited separation of concerns
* Minimal input validation
* Limited error handling
* Lack of object-oriented architecture

### Enhancement Implemented

To address these concerns, the application was redesigned using a modular object-oriented architecture.

Key improvements included:

* Creation of dedicated classes
* Encapsulation of course management functionality
* Improved validation and defensive programming
* Enhanced maintainability and scalability
* Separation of business logic from user interface functionality


## Algorithms and Data Structures Analysis

### Strengths

The original implementation effectively utilized:

* Hash tables through unordered maps
* Vectors for prerequisite storage
* Efficient course lookup operations

### Areas for Improvement

The application treated prerequisites as simple text values and lacked the ability to analyze prerequisite relationships.

Limitations included:

* No dependency analysis
* No graph traversal capabilities
* No prerequisite pathway generation
* No circular dependency detection

### Enhancement Implemented

The enhanced version models prerequisite relationships as a graph.

New capabilities include:

* Graph-based prerequisite analysis
* Depth-First Search (DFS) traversal
* Recursive prerequisite path exploration
* Circular dependency detection
* Improved dependency validation

These enhancements demonstrate the application of advanced data structures and algorithmic problem solving.


## Database Analysis

### Strengths

The original application successfully processed and stored data from CSV files.

Benefits included:

* Simple implementation
* Easy file portability
* Structured course records

### Areas for Improvement

Several limitations were identified:

* No persistent storage
* No relational data model
* Limited scalability
* No database querying capabilities
* Data existed only during program execution

### Enhancement Implemented

The database enhancement introduced SQLite integration.

Major improvements included:

* Relational database design
* Persistent storage
* SQL-based data management
* Normalized data structure
* Prepared SQL statements
* Improved data integrity and validation

This enhancement transformed the application from a file-based system into a database-driven solution.


## Course Outcomes Demonstrated

The enhancements developed from this code review demonstrate all five Computer Science program outcomes.

### Outcome 1

Design and evaluate computing solutions that support organizational goals and decision making.

* Enhanced advising functionality
* Improved information management
* Better support for course planning

### Outcome 2

Demonstrate professional communication and collaboration.

* Technical documentation
* Code review presentation
* Enhancement narratives
* ePortfolio development

### Outcome 3

Apply algorithmic principles and data structures.

* Graph implementation
* DFS traversal
* Dependency analysis
* Complexity evaluation

### Outcome 4

Use software engineering practices and technologies to create computing solutions.

* Object-oriented design
* Modular architecture
* Database integration
* Software enhancement implementation

### Outcome 5

Apply security-minded practices throughout the development process.

* Input validation
* Defensive programming
* Error handling
* Prepared SQL statements
* Secure data management


## Summary

The code review provided a comprehensive analysis of the original Course Advising System and established a roadmap for enhancement throughout the capstone project.

The review identified opportunities to improve:

* Software architecture
* Algorithmic complexity
* Database functionality
* Security practices
* Maintainability

The resulting enhancements demonstrate significant growth in software engineering, algorithms and data structures, database management, and secure software development. Together, these improvements transformed the original artifact into a more scalable, maintainable, and professionally designed software solution that reflects the knowledge and skills developed throughout the Computer Science program.
