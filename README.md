# EduTrack: Student Learning and Results Management System

EduTrack is a simple, console-based Python application created for the PROG211 Object-Oriented Programming 1 assignment. It demonstrates OOP by managing student records, courses, enrolments, and academic results.

## Features
- Register and display students
- Search for students by ID or name
- Add and display courses
- Enrol students in courses
- Record marks for enrolled courses
- Calculate grades
- Display a portal summary
- Validate common user input
- Demonstrate Python lists and dictionaries

## OOP Concepts
- **Classes and objects:** `Student`, `Course`, and `LearningPortal`
- **Constructors:** `__init__()` initializes objects
- **Attributes:** Store student and course information
- **Instance methods:** Perform actions on individual objects
- **Class method:** `Student.get_portal_summary()`
- **Static methods:** `Student.grade_for()` and `LearningPortal.valid_email()`
- **Object interaction:** Students enrol in courses, and courses track enrolled students
- **Data structures:** Lists and dictionaries store records

## Requirements
- Python 3
- No third-party packages are required.

## How to Run
1. Ensure Python 3 is installed.
2. Save the source code as `main.py`.
3. Open a terminal in the folder containing `main.py`.
4. Run `python main.py`. On some Windows systems, use `py main.py`.
5. Follow the numbered menu.

## Example Workflow
1. Display sample students.
2. Search for a student by ID or name.
3. Display courses.
4. Enrol a student in a course.
5. Record a mark for an enrolled course.
6. View the portal summary.
7. Choose the exit option.

## Data Structures
- `self.students = []` stores student objects in a list.
- `self.courses = {}` stores course objects in a dictionary keyed by course code.
- `self.enrolled_courses = []` stores courses associated with a student.
- `self.results = {}` stores marks by course code.

## Digital Public Goods (DPG) Considerations
- **Open source:** The code can be shared under the included MIT License.
- **Accessibility:** A numbered text menu and plain-language prompts provide a simple interface.
- **Privacy:** Sample records are for demonstration. This prototype has no authentication, encryption, or access controls; do not use it to store sensitive real student data.
- **Modularity:** Student, Course, and LearningPortal have separate responsibilities.

## Limitations and Future Improvements
- Records are stored in memory and are lost when the program closes.
- The interface is console-based.
- There is no login system or role-based access control.
- Future improvements could include SQLite storage, authentication, report export, and accessibility enhancements.

## Project Files
- `main.py` — Python source code
- `README.md` — project overview and running instructions
- `LICENSE` — open-source licence

## Author
Student: [Enter your name]  
Course: PROG211 — Object-Oriented Programming 1  
Institution: Limkokwing University of Creative Technology, Sierra Leone

## Licence
This project is released under the MIT License. See `LICENSE` for details.
