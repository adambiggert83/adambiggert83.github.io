# Database Enhancement

## Overview

The original Course Advising System relied entirely on CSV files for data storage. While effective for small datasets, this approach lacked persistence, relational structure, and database management capabilities.

This enhancement introduced SQLite integration to provide persistent storage, relational database functionality, and secure data management practices.


## Skills Demonstrated

* SQL
* SQLite
* Database Design
* Relational Databases
* Data Persistence
* Prepared Statements
* Data Integrity
* Secure Data Management


## Before Enhancement

The original implementation:

* Used CSV files exclusively
* Stored data only in memory
* Had no relational structure
* Had no database querying capabilities
* Lost data when the application closed


## After Enhancement

The enhanced application uses SQLite to store and manage course information.

Major improvements include:

* Persistent data storage
* Relational database design
* SQL queries
* Prepared statements
* Improved scalability
* Enhanced data integrity


## Database Design

### Courses Table

Stores course information:

* Course Number
* Course Title

### Prerequisites Table

Stores prerequisite relationships:

* Course Number
* Prerequisite Number

This design allows prerequisite relationships to be managed efficiently while maintaining normalization principles.


## Key Improvements

### SQLite Integration

Added a lightweight relational database engine directly into the application.

### Persistent Storage

Course information remains available between application executions.

### Prepared Statements

Prepared statements improve reliability and support secure database interactions.

### Data Integrity

Database constraints improve consistency and reliability of stored information.


## Why This Enhancement Matters

Modern applications rely heavily on databases for data storage and management.

This enhancement demonstrates practical experience with database technologies, relational design, and secure data handling practices that are widely used throughout the software and cybersecurity industries.


## Screenshots

*Insert screenshots showing SQLite tables, query results, and application output here.*


## Downloads

* [Original Artifact](Original-CS300-Course-Advising-System.zip)
* [Enhanced Artifact](Enhancement3-Databases.zip)
* [Enhancement Narrative](Enhancement3Narrative.docx)
