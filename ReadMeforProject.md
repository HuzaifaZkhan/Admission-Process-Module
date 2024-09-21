Admission Process and Student Management System
This project is a Student Management System for the National University of Computer and Emerging Sciences (NUCES). It provides a streamlined process for managing student admissions, generating merit lists, and searching existing student information, ensuring data persistence through file handling.

Purpose
The system serves two main functions:

Managing Student Data: View, search, and manage the history of current students, including their roll numbers, names, departments, semesters, and GPAs.
Handling New Admissions: Automates the admission process by guiding new students through department selection, test-taking, merit calculation, and admission decisions.
Features
1. Student Data Management
Displays student history, including roll number, name, department, semester, and GPA.
Allows searching for specific student information using the roll number.
2. New Admissions
Guides new students through an admission process, including:
Department selection.
Administering a department-specific test (CS, FSM, EE).
Merit calculation based on academic and test scores.
Saves the admission data to files for future reference.
3. Merit List Generation
Generates and displays a merit list of admitted students with the following information:
Name.
Matric and FSC marks.
Department.
Test marks and overall merit score.
Admission status (admitted/rejected).
4. Key Features
Menu-Driven Interface: A simple and user-friendly menu that guides users through the various options.
File Handling: The system uses files to store and retrieve student data, ensuring data persistence across sessions.
Department-Specific Tests: The system administers specific tests based on the department selected by the student (CS, FSM, EE).
Merit Calculation: A comprehensive merit score is calculated for each student based on their academic performance and test results.
Status Determination: Based on merit scores and department-specific cutoffs, students are either granted admission or rejected.
Data Storage: All admitted students' information is saved in separate files for future reference and management.
Technologies Used
Programming Language: C++
File Handling: Text files for storing student and admission data.
How to Use
Clone the repository:
bash
Copy code
git clone https://github.com/HuzaifaZKhan/Admission-Process-Module.git
Navigate to the project directory and compile the C++ files.
Run the executable and follow the menu-driven instructions.
For viewing existing students, use the View Students option.
For new admissions, use the New Admission option.
To generate a merit list, use the Generate Merit List option.
Future Improvements
Graphical User Interface (GUI): Add a graphical interface to enhance user interaction.
Database Integration: Integrate with a database system for more scalable and secure data handling.
Enhanced Merit Calculation: Add more flexible criteria for merit calculation.