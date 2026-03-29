#  Smart Student Task and Study Tracker



#  1. Project Overview

The **Smart Student Task and Study Tracker** is a command-line based application developed using Python. The primary aim of this project is to assist students in managing their academic tasks in a structured and efficient manner.

In modern academic life, students are required to handle multiple responsibilities such as assignments, projects, exams, and daily study routines. Due to this workload, it becomes difficult to remember all tasks and deadlines, often leading to stress and poor performance.

This project provides a simple yet effective solution by allowing users to store, manage, and track their tasks in an organized way.



#  2. Problem Statement

Students commonly face the following issues:

* Difficulty in remembering assignment deadlines
* Poor time management
* Lack of proper planning tools
* Increased stress due to last-minute work
* Inefficient tracking of completed and pending tasks

Although many task management tools are available, they often:

* Require internet connectivity
* Have complex interfaces
* Include unnecessary features

Therefore, a need arises for a **simple, lightweight, and offline task management system** specifically designed for students.



#  3. Objectives of the Project

The main objectives of this project are:

* To develop a simple and easy-to-use task manager
* To help students organize their daily academic activities
* To provide features for adding, viewing, and deleting tasks
* To improve productivity and time management skills
* To demonstrate the practical application of programming concepts

---

#  4. Solution Approach

This project implements a **menu-driven command-line system** where users interact with the program by selecting options.

The system allows users to:

* Add new tasks
* View all stored tasks
* Delete tasks when completed

The design focuses on simplicity and usability, ensuring that even beginners can operate the system without difficulty.



#  5. Features

### Core Features

*  Add Task
* 📋View Tasks
*  Delete Task

###  Additional Characteristics

* Lightweight application
* Runs offline
* Fast execution
* Simple user interface
* Easy to understand code

---

#  6. Technologies Used

| Component            | Technology               |
| -------------------- | ------------------------ |
| Programming Language | Python                   |
| Interface            | Command Line (CLI)       |
| Data Handling        | List / JSON (optional)   |
| Platform             | Windows / Linux Terminal |

---

#  7. Working of the System (Step-by-Step Explanation)

The program works using a continuous loop that displays a menu and performs actions based on user input.

### Step 1: Program Start

The program initializes an empty list to store tasks.

### Step 2: Display Menu

The user is presented with options:

1. Add Task
2. View Tasks
3. Delete Task
4. Exit

### Step 3: User Input

The user selects an option by entering a number.

### Step 4: Perform Operation

* If user selects **Add Task** → program asks for task input and stores it
* If user selects **View Tasks** → program displays all tasks
* If user selects **Delete Task** → program removes selected task
* If user selects **Exit** → program terminates

### Step 5: Loop Continues

The program repeats until the user exits.



#  8. Algorithm

1. Start program
2. Initialize task list
3. Display menu
4. Take user input
5. Perform operation based on input
6. Update task list
7. Repeat until exit
8. End program



#  9. Output Representation (Terminal Style)

##  Main Menu


C:\Users\Student\Desktop>python main.py

1. Add Task
2. View Tasks
3. Delete Task
4. Exit

Enter choice:




##  Adding a Task


Enter choice: 1

Enter task: Complete AI assignment
Task added successfully

1. Add Task
2. View Tasks
3. Delete Task
4. Exit




##  Viewing Tasks


Enter choice: 2

1. Complete AI assignment

1. Add Task
2. View Tasks
3. Delete Task
4. Exit




#  10. Project Structure


student-task-tracker/
│── main.py
│── README.md
│── tasks.json (optional)
│── screenshots/ (optional)




#  11. Installation and Execution Guide

## Step 1: Install Python

Download and install Python from official website.

## Step 2: Download Project

Clone repository:


git clone https://github.com/your-username/your-repo-name.git


## Step 3: Open Terminal

Navigate to project folder:


cd your-repo-name


## Step 4: Run Program


python main.py




#  12. Challenges Faced

* Handling invalid user input
* Managing task storage effectively
* Designing a simple interface
* Ensuring program does not crash



#  13. Advantages

* Simple and easy to use
* No internet required
* Beginner-friendly
* Efficient for basic task management
* Lightweight and fast



#  14. Limitations

* No graphical user interface
* No reminder system
* Limited features
* No multi-user support

---

#  15. Future Scope

* Add GUI using Tkinter
* Implement reminders and notifications
* Use database for storage
* Develop mobile or web version
* Add priority and deadline features

---

#  16. Learning Outcomes

Through this project, I gained knowledge of:

* Python programming
* Control structures and loops
* File handling and data storage
* Problem-solving techniques
* Real-world application development



# 👨‍💻 17. Author

** Name:Rasika Jain**
Registration Number: 24BCE10029



#  18. References

* Python Official Documentation
* Online tutorials and learning resources
* Course materials



#  Final Conclusion

This project successfully demonstrates how basic programming concepts can be used to develop practical solutions for real-world problems. The Smart Student Task and Study Tracker is a simple yet powerful tool that helps students manage their tasks effectively and improve productivity.
