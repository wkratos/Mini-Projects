# Student Grade Manager 📚

A simple C program to manage students and their grades. You can add students, assign grades, list all students, and calculate averages. Built as a practice project for handling structs, arrays, and basic I/O in C.

## ✨ Features
- **Add Students**: Create new student records (up to 100 students, unique names)
- **List Students**: View all registered students
- **Add Grades**: Assign grades (0–100) to students (up to 20 grades per student)
- **Calculate Averages**: View a student's average grade
- **Interactive Menu**: Text-based interface for easy navigation

## 📋 Requirements
- C compiler (gcc, clang)
- Make utility
- Standard C library

## 📁 Project Structure
```
Program/
├── grade_manager.h  # Header file (structs + function prototypes)
├── student.c        # Student functions (add, list, find, grades, average)
├── io.c             # Utility functions (strlen, putstr, putnbr, readline, atoi, etc.)
├── main.c           # Program entry point + menu loop
└── Makefile         # Build automation
```

## 🛠️ Build & Run

### Compile
```bash
make
```

### Run
```bash
./grade_manager
```

### Clean (remove .o files & binary)
```bash
make clean
```

## 💡 Example Usage
```
=== Student Grade Manager ===
1) Add student
2) List students
3) Add grade
4) Show student average
0) Quit
> 1
Student name: Alice
> 3
Student name: Alice
Grade: 95
> 4
Student name: Alice
Average: 95.00
```

## 📝 License
MIT License - See README.md in parent directory for details
Student name: Alex
Added.

> 3
Student name: Alex
Grade (0-100): 40
Grade added.

> 3
Student name: Alex
Grade (0-100): 60
Grade added.

> 3
Student name: Alex
Grade (0-100): 80
Grade added.

> 4
Student name: Alex
Average of Alex: 60

> 0
y3awnrebi

## Notes

- Names must be unique and non-empty.

- Grades must be between 0 and 100.

- Each student can store up to 20 grades.

- The class can have up to 100 students.