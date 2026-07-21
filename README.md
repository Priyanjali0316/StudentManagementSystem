# Student Management System

## Project Overview
The **Student Management System** is a Python-based application developed as part of a Git and GitHub collaborative version control lab. The project demonstrates team collaboration using branches, commits, merging, conflict resolution, stashing, recovery, and release management done for DevOps Lab.

## Team Members
- **Developer A** – Repository creation, project setup, report module, and repository management.
- **Developer B** – Attendance module, marks module, and feature development.

## Project Structure

```
StudentManagementSystem/
│── README.md
│── student.py
│── attendance.py
│── marks.py
│── report.py
```

## Modules

### student.py
- Add student details
- View student information
- Update student records
- Delete student records

### attendance.py
- Record student attendance
- View attendance history
- Calculate attendance percentage

### marks.py
- Enter student marks
- Update marks
- Calculate total and average marks
- Display grades

### report.py
- Generate student performance reports
- Display attendance summary
- Display marks summary

## Technologies Used
- Python 3.x
- Git
- GitHub

## Git Workflow Used
- Repository initialization
- GitHub remote repository
- Branch creation
- Feature development
- Commits
- Merge operations
- Merge conflict resolution
- Stashing
- Git Reflog recovery
- Cherry-pick
- Tags (Version 1.0)
- .gitignore configuration

## Branches
- `main`
- `feature-attendance`
- `feature-marks`
- `feature-registration`
- `bugfix`

## How to Run

1. Clone the repository

```bash
git clone <repository-url>
```

2. Move into the project folder

```bash
cd StudentManagementSystem
```

3. Run the desired module

```bash
python student.py
```

or

```bash
python attendance.py
```

or

```bash
python marks.py
```

or

```bash
python report.py
```

## Learning Outcomes

This project demonstrates the use of:

- Git repository initialization
- Remote repositories using GitHub
- Feature branching
- Commit management
- Merge and conflict resolution
- Delete/modify conflict handling
- Stash operations
- Reflog recovery
- Cherry-picking commits
- Repository history analysis
- Release tagging
- Ignoring unnecessary files using `.gitignore`

## Version

**Current Version:** v1.0

## License

This project is developed for educational purposes as part of the Git and GitHub Laboratory.
