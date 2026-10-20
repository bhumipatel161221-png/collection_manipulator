# Collection Manipulator – Student Data Organizer

## Description
A Python console application that manages student records using List, Tuple, Set, and Dictionary. Demonstrates string formatting, mutability/immutability, type casting, and the `del` keyword.

## Features
- Add, display, update, delete students.
- Store ID and DOB as an immutable tuple.
- Maintain a set of unique subjects.
- Use a dictionary for fast lookup by student ID.
- Menu-driven interface with input validation.

## Assumptions
- Student ID is an integer.
- Date of Birth is a string in YYYY-MM-DD format.
- Subjects are entered as comma-separated values.
- Data is not persisted to disk.

## How to Run
1. Ensure Python 3.x is installed.
2. Clone the repository.
3. Run: `python student_data_organizer.py`

## Sample Output
============================================================
Welcome to the Student Data Organizer!
============================================================
This program manages student records using lists, tuples,
sets, and dictionaries. You can add, display, update, delete
students and view all unique subjects offered.


==================================================
Select an option:
1. Add Student
2. Display All Students
3. Update Student Information
4. Delete Student
5. Display Subjects Offered
6. Exit
==================================================
Enter your choice: 1

--- Add Student ---
Student ID: 100
Name: bhumi
Age: 21
Grade: A+
Date of Birth (YYYY-MM-DD): 20-07-2005
Subjects (comma-separated): math, science, english

Student added successfully! (ID: 100)

==================================================
Select an option:
1. Add Student
2. Display All Students
3. Update Student Information
4. Delete Student
5. Display Subjects Offered
6. Exit
==================================================
Enter your choice: 2

--- All Students ---
Student ID: 100 | Name: bhumi | Age: 21 | Grade: A+ | Subjects: math, science, english

==================================================
Select an option:
1. Add Student
2. Display All Students
3. Update Student Information
4. Delete Student
5. Display Subjects Offered
6. Exit
==================================================
Enter your choice: 2

--- All Students ---
Student ID: 100 | Name: bhumi | Age: 21 | Grade: A+ | Subjects: math, science, english

==================================================
Select an option:
1. Add Student
2. Display All Students
3. Update Student Information
4. Delete Student
5. Display Subjects Offered
6. Exit
==================================================
Enter your choice: 2

--- All Students ---
Student ID: 100 | Name: bhumi | Age: 21 | Grade: A+ | Subjects: math, science, english

==================================================
Select an option:
1. Add Student
2. Display All Students
3. Update Student Information
4. Delete Student
5. Display Subjects Offered
6. Exit
==================================================
Enter your choice: 
Invalid choice. Please enter a number between 1 and 6.

==================================================
Select an option:
1. Add Student
2. Display All Students
3. Update Student Information
4. Delete Student
5. Display Subjects Offered
6. Exit
==================================================
Enter your choice: 2

--- All Students ---
Student ID: 100 | Name: bhumi | Age: 21 | Grade: A+ | Subjects: math, science, english

==================================================
Select an option:
1. Add Student
2. Display All Students
3. Update Student Information
4. Delete Student
5. Display Subjects Offered
6. Exit
==================================================
Enter your choice: 
Invalid choice. Please enter a number between 1 and 6.

==================================================
Select an option:
1. Add Student
2. Display All Students
3. Update Student Information
4. Delete Student
5. Display Subjects Offered
6. Exit
==================================================
Enter your choice: 
Invalid choice. Please enter a number between 1 and 6.

==================================================
Select an option:
1. Add Student
2. Display All Students
3. Update Student Information
4. Delete Student
5. Display Subjects Offered
6. Exit
==================================================
Enter your choice: 
Invalid choice. Please enter a number between 1 and 6.

==================================================
Select an option:
1. Add Student
2. Display All Students
3. Update Student Information
4. Delete Student
5. Display Subjects Offered
6. Exit
==================================================
Enter your choice: 3

--- Update Student Information ---
Enter Student ID to update: 100
Current details: Name: bhumi, Age: 21, Grade: A+, Subjects: math, science, english
What would you like to update?
1. Age
2. Subjects
Enter choice (1/2): 1
Enter new age: 20
Age updated successfully.

==================================================
Select an option:
1. Add Student
2. Display All Students
3. Update Student Information
4. Delete Student
5. Display Subjects Offered
6. Exit
==================================================
Enter your choice: 4

--- Delete Student ---
Enter Student ID to delete: 100
Student ID 100 deleted successfully.

==================================================
Select an option:
1. Add Student
2. Display All Students
3. Update Student Information
4. Delete Student
5. Display Subjects Offered
6. Exit
==================================================
Enter your choice: 6

Thank you for using the Student Data Organizer. Goodbye!

## Author
[bhumi]
