# Python Capstone Project

Jupyter notebooks tracking a Python training course, from fundamentals through a final capstone project: a console-based **Smart Training Center Management System**.

## Notebooks

| Notebook | Description |
|---|---|
| [Python_Fundamentals_part1.ipynb](Python_Fundamentals_part1.ipynb) | Core Python: variables/data types, syntax tables, worked examples, common mistakes, guided practice. |
| [Intermediate Python Exercises.ipynb](Intermediate%20Python%20Exercises.ipynb) | TODO-style exercises covering lists, dicts, sets, strings, dates, iterators, and recursion. |
| [Python_Post_Training_New_Tasks_Assessment.ipynb](Python_Post_Training_New_Tasks_Assessment.ipynb) | Assessment with new multilevel tasks in new contexts, for after completing Fundamentals Parts 1 and 2. |
| [Python_Error_Handling_and_OOP_Workbook.ipynb](Python_Error_Handling_and_OOP_Workbook.ipynb) | Combined workbook: exception handling and validation, feeding into object-oriented programming exercises. |
| [Python_Fundamentals_Part2.ipynb](Python_Fundamentals_Part2.ipynb) | Conditionals, loops, functions, error handling, file handling, and OOP basics. |
| [Python_Capstone_Project_Training_Center_Management_System.ipynb](Python_Capstone_Project_Training_Center_Management_System.ipynb) | Final capstone project, described below. |

## Capstone: Smart Training Center Management System

A console-based system that manages trainees, courses, attendance, assessment scores, course completion, certificate eligibility, data persistence, and summary reports, using variables, type conversion, string processing, lists/tuples/sets/dictionaries, NumPy arrays, conditionals, loops, functions, error handling, JSON/CSV file I/O, and OOP (`Trainee`, `Course`, `TrainingCenter` classes).

**Scenario:** a training center offers courses, each with a code, title, capacity, passing score, minimum attendance requirement, and fixed schedule. The system registers trainees, enrolls them in courses, records attendance and scores, calculates performance, determines completion and certificate eligibility, and saves/reloads data through a menu-driven console interface.

**Data files:**
- [training_center.json](training_center.json): course catalog and enrollment data (input).
- [py101_report.csv](py101_report.csv): generated summary report for the PY101 course (output), including trainee scores, attendance, pass/fail status, and certificate eligibility.
