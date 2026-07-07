# Student Grade Manager Pro

Student Grade Manager Pro is a Python application that allows users to manage student records and marks through a simple command-line interface. The program stores data in a JSON file, making it possible to save records between sessions.

## Features

* Add new students and marks
* View all student records
* Search for a student by name
* Update student marks
* Delete student records
* Calculate class average
* Identify the top-performing student
* Sort students by marks
* Display class statistics
* Automatic data saving using JSON

## Technologies Used

* Python 3
* JSON for data storage

## Project Structure

```text
student-grade-manager-pro/
│
├── main.py
├── students.json
└── README.md
```

## How It Works

The application stores student names and marks in a dictionary and saves the data to a JSON file. When the program starts, it loads any previously saved records. Users can manage student information through a menu-driven interface.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/student-grade-manager-pro.git
```

2. Navigate to the project folder:

```bash
cd student-grade-manager-pro
```

3. Run the application:

```bash
python main.py
```

## Example Menu

```text
===== STUDENT GRADE MANAGER PRO =====
1. Add Student
2. View Students
3. Search Student
4. Update Mark
5. Delete Student
6. Class Average
7. Top Student
8. Sort Students
9. Statistics
10. Exit
```

## Learning Outcomes

This project demonstrates:

* Functions
* Loops
* Conditional statements
* Dictionaries
* File handling
* JSON data storage
* Sorting algorithms
* Searching techniques
* Input validation
* Error handling

## Future Improvements

Potential enhancements include:

* Graphical User Interface (GUI) using Tkinter
* Exporting data to CSV files
* Multiple subjects per student
* Grade reports and transcripts
* Data visualization using Matplotlib
* Database integration with SQLite

## Author
Mmapaseka Kgaka
Developed as a Python portfolio project to practice programming fundamentals and demonstrate software development skills.
