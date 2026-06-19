# Algorithms and Data Structures Enhancement

## Overview

The original Course Advising System stored prerequisite information but treated prerequisite relationships as simple text values. The application could display prerequisites but could not analyze relationships between courses.

This enhancement expanded the application by modeling prerequisite relationships as a graph structure and implementing graph traversal algorithms.


## Skills Demonstrated

* Data Structures
* Graph Theory
* Depth-First Search (DFS)
* Recursion
* Algorithm Design
* Complexity Analysis
* Dependency Analysis
* Problem Solving


## Before Enhancement

The original implementation:

* Stored prerequisites in vectors
* Displayed prerequisite text
* Performed no relationship analysis
* Could not detect dependency issues
* Could not traverse prerequisite chains


## After Enhancement

The enhanced version models course relationships as a graph.

New capabilities include:

* Graph-based prerequisite analysis
* Recursive traversal
* DFS implementation
* Full prerequisite pathway generation
* Circular dependency detection


## Key Improvements

### Graph Representation

Each course functions as a node within a graph structure.

### Depth-First Search (DFS)

DFS is used to recursively analyze prerequisite relationships and display prerequisite pathways.

### Dependency Analysis

The system can now evaluate complete prerequisite chains rather than simply displaying immediate prerequisites.

### Circular Dependency Detection

The enhancement identifies invalid prerequisite loops and prevents infinite recursion.


## Example Output

```plaintext
Prerequisite Path for CS499

CS499
 └── CS400
      └── CS300
           └── CS200
```


## Why This Enhancement Matters

Graph structures are commonly used to model relationships, dependencies, and networks.

This enhancement demonstrates the practical application of advanced data structures and algorithms to solve real-world problems and improve system functionality.


---

### Downloads

| Resource | Link |
|---|---|
| Original Artifact | [Download](Original-CS300-Course-Advising-System.zip) |
| Enhancement Two Artifact | [Download](Enhancement2-Algorithms-DataStructures.zip) |
| Enhancement Two Narrative | [Download](Enhancement2Narrative.docx) |
