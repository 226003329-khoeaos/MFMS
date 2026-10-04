# PAP-Project

## Municipal Financial Management System (MFMS)

### Group members:
Student number | Name and surname
--- | ---
[226106144] | [Hitjevi Ngeama]
[226141152] | [Andreas Werner]
[226142094] | [Ndapewa Kanguloshi]
[226019497] | [Innocentia Ikera]
[225059096] | [Garrison Jr Shilongo]
[226003329] | [Rhiolin Khoeaos]
[226043789] | [Samuel Shaningwa]

### Instructions for running the source code
All code was developed and tested using VS Code and GCC. To run the code:

1. Open the terminal in VS Code.
2. Compile the files using GCC:
   `gcc main.c employees.c budget.c suppliers.c assets.c reports.c -o mfms`
3. Enter the prompted input from the main menu.

No online compiler is used. You must have GCC installed on your computer.

### Github repository link
https://github.com/226003329-khoeaos/MFMS

Student [226106144] [Hitjevi Ngeama] (STUDENT 3)

**Overview**
This module provides functionality to manage supplier data within a municipal financial management system. It allows users to add, search, and display supplier information. It ensures that all supplier records are validated before being stored, maintaining accurate contact details for the municipality.

**Features**
- **Add Suppliers:** Register new suppliers with validation for unique positive IDs and non-empty names.
- **Display Suppliers:** View all registered suppliers in a formatted list showing their full details.
- **Search Suppliers:** Find suppliers by either their unique ID or their exact name (using string comparison).
- **Supplier Reports:** Generate a summary report displaying all registered suppliers and the total count.

Student [226019497] [Inocentia Ikera] (Student 4)
**Overview**
The Employee management module is a crucial part in the Municipality Financial Management System. It allows users or management to add, display, and search the system for employees. It retains integrity of the employee files.

**Features**
• **addEmployee**: Inserts a new employee record into the database array and increments the total count.
• **displayEmployee**: Goes through the database to print the records of all currently stored employees.Overview
This module provides functionality to manage supplier data within a municipal financial management system. It allows users to add, search, and display supplier information. It ensures that all supplier records are validated before being stored, maintaining accurate contact details for the municipality.

Features
- Add Suppliers: Register new suppliers with validation for unique positive IDs and non-empty names.
- Display Suppliers: View all registered suppliers in a formatted list showing their full details.
- Search Suppliers: Find suppliers by either their unique ID or their exact name (using string comparison).
- Supplier Reports: Generate a summary report displaying all registered suppliers and the total count.


Project Overview
The Municipal Financial Management System (MFMS) is a foundational C-based software
application developed as part of Project A for the Programming in Practice course. It
provides a command-line interface to help local government entities manage core
administrative and financial operations, including employee records, departmental budgets,
supplier details, asset inventories, and summary reports.

Group Members
| Student Number | Name and Surname | Assigned Module |

|225059096 | Garrison Jr Shilongo | Student 5: Reports Module & Data Integration
|226106144 | Hitjevi Ngeama | Student 3: Supplier Management Module
|226141152 | Andreas Werner | Student 2: Budget Management Module
|26003329 | Rhiolin Khoeaos | Student 4: Asset Management Module
|226019497 | Innocentia Ikera | Student 1: Employee Management Module
|226043789 | Samuel Shaningwa | Student 6: Main Menu, Integration & Input Validation
|226142094 | Ndapewa Kanguloshi | Student 7: Testing, Documentation & Git Coordination

System Features & Modules
Employee Management : Add, display, and search employee records, including salary and
allowance calculations.
Budget Management : Track departmental budget allocations, expenditures, remaining
balances, and over-budget flags
Supplier Management : Store, display, and search municipal suppliers using unique IDs and
string comparisons.
Asset Management : Register and search municipal assets such as vehicles, tech, and
equipment by type or department
Reports Module : Aggregate and display summary analytics across employees, budgets,
suppliers, and assets

Instructions for Running the Source Code
All code was developed and tested using VS Code and GCC. To run the code:
1. Open the terminal in VS Code in the project directory.
2. Compile all source files together using GCC:
bash
gcc main.c employees.c budget.c suppliers.c assets.c reports.c -o mfms

3. Run the executable and navigate using the interactive main menu.
• **searchEmployee**: Queries the database to find and view a specific employee's information based on a search criteria, like the name of the employee, using string comparison.

"Submitted by []"
