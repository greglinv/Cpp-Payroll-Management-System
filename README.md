# C++ Payroll and Employee Management System

A foundational command-line tool designed to process employee data, manage payroll states, and automate financial raises through file-based input/output.

## Engineering Highlights

* **File Stream Processing:** Implemented robust file I/O to parse employee commands (NEW, RAISE, PAY, FIRE) from external text files.
* **State Management:** Manages the lifecycle of an employee object, including employment status and cumulative balance tracking.
* **Data Structures:** Utilizes C++ Vectors to manage dynamic collections of objects, ensuring efficient memory handling and access.
* **Logic Automation:** Built a raise-calculation engine that applies percentage-based increases to base pay rates across the employee database.

## Tech Stack

* **Language:** C++
* **Standard Library:** fstream, vector, iostream
* **Architecture:** Object-Oriented Programming (OOP)

## Installation and Usage

1. Clone the repository.
2. Compile the project using a C++ compiler: `g++ main.cpp Employee.cpp -o PayrollManager`.
3. Ensure an `input.txt` file is present in the directory with formatted commands.
4. Run the executable: `./PayrollManager`.
5. Check `output.txt` for the generated payroll report.
