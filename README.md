# LMS_OOP

## Project Overview
LMS__OOP is a library management system developed with a strong emphasis on Object-Oriented Programming (OOP) principles. The system implements logic for managing library publications and patrons, supports file handling for saving and loading the system's state, and employs multi-threading to handle IO-bound tasks concurrently. Additionally, it includes a custom exception inheriting from ArithmeticException to enhance error handling.

This system was developed over four sprints, each lasting one week, following Agile Methodology as part of a course project. Full Javadoc documentation has been implemented and can be generated using the provided run instructions.

## Features and Benefits
The system offers various functionalities to manage library operations efficiently and uses a menu-driven interface to receive user input.

### Publications Management
+ View all publications in the library.
+ Add publications to the library by specifying details like title, author, copyright year, and runtime (for videos).
+ Check out a publication to a patron.
+ Check in a borrowed publication.  
### Patron Management
+ List all patrons.
+ Add new patrons. 
### State Management
Multi-threading has been implemented for these I/O-bound tasks to add to the responsiveness of the system.
+ Save the current state of the system to a file.
+ Load the library to a previously saved state.
+ Load test data.

## Run Instructions

### Prerequisites
+ Java: Ensure Java is installed (Java 17 was used for development).
+ Apache Ant: Install the Apache Ant build tool (Apache Ant(TM) version 1.10.12 was used).
### Running the Program
1. Build the program by running the following command:
   'ant'
2. Run the main class:
   'java mdi.LibraryManager
### Test Files
+ The publications test file that contains sample publication data is located in mdi/Publications.txt
+ The patrons test file that contains sample patrons data is located in mdi/Patrons.txt

### User Interface
Upon running the program, the following menu should be displayed:
UTA Central Library

=========
Main Menu
=========

Publications
1) List
2) Add
3) Check out
4) Check in

Patrons
5) List
6) Add

Files
7) Load Test Data
8) Save
9) Load
0) Exit

