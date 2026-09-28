# Student Management System (Python OOP)

A simple command-line Student Management System built with Object-Oriented Programming in Python. It takes a student's details as input, displays them, and calculates the grade from the marks.

## Table of Contents

- [Features](#features)
- [Concepts Covered](#concepts-covered)
- [Requirements](#requirements)
- [How to Run](#how-to-run)
- [Grading Scale](#grading-scale)
- [Sample Output](#sample-output)
- [Code Overview](#code-overview)
- [Project Structure](#project-structure)
- [Possible Improvements](#possible-improvements)
- [License](#license)

## Features

- `Student` class that stores:
  - Student ID
  - Name
  - Age
  - Marks
- `display_student()` prints the student's details
- `calculate_grade()` prints the grade based on marks
- Takes user input from the console

## Concepts Covered

- Class
- Object
- Constructor (`__init__`)
- Methods
- Conditional statements (`if` / `elif` / `else`)

## Requirements

- Python 3.6 or higher
- No external libraries needed

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>
   ```

2. Run the program:

   ```bash
   python student_management.py
   ```

3. Enter the student's details when prompted.

## Grading Scale

| Marks | Grade |
|---|---|
| 90 and above | A |
| 80 - 89 | B |
| 70 - 79 | C |
| 60 - 69 | D |
| Below 60 | F |

## Sample Output

```
Enter Student ID: 101
Enter Name: Aisha
Enter Age: 20
Enter Marks: 85

--- Student Details ---
Student ID : 101
Name       : Aisha
Age        : 20
Marks      : 85
Grade      : B
```

## Code Overview

```python
class Student:

    def __init__(self, student_id, name, age, marks):
        ...

    def display_student(self):
        ...

    def calculate_grade(self):
        ...
```

| Method | Purpose |
|---|---|
| `__init__(student_id, name, age, marks)` | Constructor that stores the student's data in the object |
| `display_student()` | Prints the student ID, name, age, and marks |
| `calculate_grade()` | Uses conditional statements to determine and print the grade |

## Project Structure

```
.
├── student_management.py
└── README.md
```

## Possible Improvements

- Validate input (numeric values only, marks between 0 and 100)
- Make `calculate_grade()` return the grade instead of printing it
- Store multiple students in a list and add a menu (add, view, search, delete)
- Save and load student records from a file
- Add an `if __name__ == "__main__":` guard

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
