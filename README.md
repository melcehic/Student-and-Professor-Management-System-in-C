# Student-and-Professor-Management-System-in-C
📚 Student-Professor Management System
EM Lyon Business School — C Programming Project

🧩 Project Overview
This C console application simulates a simplified academic system to manage students and professors. It uses struct, pointers, and input validation to model real-world academic relationships.

🎯 Learning Objectives
Use struct to model entities

Manage memory with pointers (malloc, free)

Validate user inputs

Simulate supervision between students and professors

👥 Managed Entities
🧑‍🎓 Students
ID (positive integer)

Full name

Program (e.g., MSc in Finance)

GPA (0.0–4.0)

👨‍🏫 Professors
ID

Full name

Department (e.g., Marketing)

Supervised students (up to 10)

⚙️ Features
Students
Add, view, search, modify, or delete a student

Professors
Add, view professors

Assign students

View a professor’s students

🔄 Example Scenarios
Assign students to a professor (max 10)

Reject invalid inputs, like GPA > 4.0 or negative IDs

View all students supervised by a professor

🧱 Constraints
Use only standard C

Use dynamic memory allocation

Validate all inputs

Ensure modular code and no memory leaks

💡 Bonus Features
Save/load data from files

Co-supervision

Sort students by GPA or program

🚀 How to Use
🔧 Compile
bash
Copier
Modifier
gcc -o management_system main.c
▶️ Run
bash
Copier
Modifier
./management_system
