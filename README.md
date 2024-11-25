# FINAL-READ-ME-FILE

ReadMe File for Python Grading System Project

Overview
This project focuses on building a comprehensive Python-based Grading System for student data management. Developed incrementally across multiple phases, the system grows from basic scalar operations to robust object-oriented designs, including advanced error handling, data sorting, and performance optimization.

Section A

Features
Prompts the user to enter the number of students in the class.
Collects each student’s full name and their grade in a single subject.
Ensures grades are valid (between 0 and 100).
Calculates and displays:
The total grade for the class.
The average grade for the class.

How to Use
Ensure Python is installed on your machine.
Open Section_A.py in an IDE (e.g., PyCharm or Visual Studio) and run the script.
Input the number of students, their names, and grades as prompted.
View the calculated class average displayed after input.

Section B

Features
Handles multiple subjects (e.g., Math, English, Science) for each student.
Stores each student's data as a tuple: (Name, [Grades]).
Computes and displays:
The average grade for each student.
The highest and lowest grades for each subject.
A summary of all students' grades and averages.

How to Use
Open Section_B.py in your IDE and run the script.
Provide the number of students, their names, and grades for each subject.
Observe detailed grade summaries and averages for individual students and subjects.

Section C

Features
Introduces dictionaries to manage data efficiently.
Allows user to:
Add new students.
Update existing grades.
Remove students.
Extends functionality to:
View grades for specific subjects across all students.
Search for a student by name to view their grades and averages.

How to Use
Open Section_C.py and execute it.
Use the provided menu to perform actions like adding students, updating grades, or searching for a student.
View results or summaries dynamically displayed based on your inputs.


Section D

Features
Modularized design with reusable functions for:
Adding/removing students.
Updating grades.
Searching for students.
Displaying data summaries.
Robust error handling to manage:
Invalid names or grades.
Missing student data.

How to Use
Run Section_D.py.
Call specific functions (e.g., add_student(), search_student()) to perform desired tasks.
Utilize detailed error messages for guidance during input errors.

Section E

Features
Student Class:
Manages individual student details.
Calculates averages and adds new grades.
Gradebook Class:
Manages a collection of students.
Provides advanced operations such as sorting students by average grade or specific subjects.
Fully tested for performance and accuracy with large datasets.

How to Use
Execute Section_E.py.
Instantiate a Gradebook and interact using methods such as add_student(), remove_student(), or sort_by_average().
View organized and user-friendly output.

Section F

Features
Custom exceptions (StudentNotFoundError, InvalidGradeError) for clear error identification.
Implements searching and sorting (e.g., bubble sort for averages).
Comprehensive testing and documentation to ensure:
Data integrity.
Reliable performance under different scenarios.

How to Use
Run Section_F.py.
Utilize implemented sorting and searching algorithms for organized results.
Test the program’s robustness by simulating edge cases like invalid inputs or empty datasets.

General Prerequisites
Install Python on your machine.
Use an IDE like PyCharm, Visual Studio, or any text editor capable of running Python scripts.
Test each section incrementally to understand its features and functionality.
This README file provides a structured guide for navigating the Python Grading System Project. Ensure to explore each phase for better understanding and utility
