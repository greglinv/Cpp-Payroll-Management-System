# C++ Payroll and Employee Management System

A foundational command-line tool designed to process employee data, manage payroll states, and automate financial raises through file-based input/output. This project serves as a demonstration of core Object-Oriented Programming (OOP) and systems thinking in C++.

## Engineering Highlights

* **File Stream Processing:** Implemented robust file I/O using `fstream` to parse complex employee commands (NEW, RAISE, PAY, FIRE) from external text files.
* **State Management:** Architected an `Employee` class to manage lifecycles, including employment status, cumulative balance tracking, and pay rate adjustments.
* **Memory & Data Management:** Utilizes C++ Vectors to manage dynamic collections of objects, ensuring efficient memory handling and sequential data access.
* **Financial Logic Automation:** Built a raise-calculation engine that applies percentage-based increases to base pay rates across the personnel database.

## Tech Stack

* **Language:** C++
* **Standard Library:** fstream (File I/O), vector (Dynamic Arrays), iostream
* **Architecture:** Object-Oriented Programming (OOP)



---

## Installation and Usage

1. **Clone the Repository**:
   ```bash
   git clone [https://github.com/greglinv/Cpp-Payroll-Management-System.git](https://github.com/greglinv/Cpp-Payroll-Management-System.git)
2. **Prepare Input Data**: Ensure an input.txt file is present in the root directory with formatted commands (e.g., NEW 101 John Doe).
3. **Compile the Project**: Use a C++ compiler (like g++) to build the executable:
   ```bash
   g++ main.cpp Employee.cpp -o PayrollManager
4. **Run the Application**:
   ```bash
   ./PayrollManager
5. **View Report**: The program will generate an output.txt file containing the processed payroll and employment status report.
