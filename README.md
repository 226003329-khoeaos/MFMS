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

Submitted by:




## BUDGET MANAGEMENT MODULE
### DESCRIPTION

This is a simple C program for managing departmental budgets in a municipal system.

### Features

- Enter departmental budgets
- Enter departmental expenditure
- Calculate the remaining budget
- Check if a department is within budget
- Identify departments that have exceeded their budget
- Display budget information for all departments

### Files

- `budget.c` - Contains the budget management functions.
- `budget.h` - Contains the function declaration used to connect the budget module to the main system.

### Budget Rules

- The minimum allocated budget is N$1000.
- Expenditure cannot be negative.
- If expenditure is greater than the allocated budget, the department is marked as `BUDGET EXCEEDED`.
- Otherwise, it is marked as `WITHIN BUDGET`.

