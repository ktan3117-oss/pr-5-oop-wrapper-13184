# pr-5-oop-wrapper-13184

Employee Management System using OOP in Python
Project Title
Employee Management System using Object-Oriented Programming (OOP)
Objective

The objective of this project is to develop an Employee Management System using various Object-Oriented Programming (OOP) concepts in Python.
This project demonstrates the practical implementation of:

Classes and Objects
Inheritance
Encapsulation
Method Overriding
Constructor and Destructor
Getter and Setter Methods
Use of super()
Use of issubclass()
Menu Driven Programming
The system allows users to:

Add Employees
Add Managers
Add Developers
Display Employee Details
Update Employee Salary
Remove Employees
Check Class Relationships
Features

Employee Class
Stores employee details:
Employee ID
Name
Age
Salary
Uses private attributes for secure data handling.
Includes getter and setter methods.
Manager Class
Inherits from Employee class.
Adds:

Department
Overrides display method.
Developer Class
Inherits from Employee class.
Adds:

Programming Language
Overrides display method.
Additional Functionalities
Update Salary
Remove Employee
Display All Records
Check subclass relationship using issubclass()
OOP Concepts Used
1. Class and Object
   
Classes are used to create employee-related objects.
Example:
Python
employee = Employee()
3. Encapsulation

Private variables are used:
Python
self.__employee_id
self.__salary
Getter and setter methods are provided.
4. Inheritance

Manager and Developer classes inherit from Employee.
Python
class Manager(Employee):
5. Method Overriding

The display() method is overridden in derived classes.
6. Constructor

Constructors initialize object data using __init__().
7. Destructor

Destructor __del__() is used to free resources.
8. super() Function

Used to call parent class constructor.
Python
super().__init__()
9. issubclass()

Checks subclass relationship.
Python
issubclass(Manager, Employee)

Project Structure

Plain text
Employee Management System
│
├── Employee Class
│
├── Manager Class
│
├── Developer Class
│
├── Functions
│   ├── Create Employee
│   ├── Create Manager
│   ├── Create Developer
│   ├── Display Details
│   ├── Update Salary
│   ├── Remove Employee
│   └── Check Subclass
│
└── Menu Driven Program
Menu Option


1. Create Employee
2. Create Manager
3. Create Developer
4. Show All Details
5. Update Salary
6. Remove Employee
7. Check Subclass
8. Exit

9.         
Sample Output

Plain text
===================================
 EMPLOYEE MANAGEMENT SYSTEM
===================================

1. Create Employee
2. Create Manager
3. Create Developer
4. Show All Details
5. Update Salary
6. Remove Employee
7. Check Subclass
8. Exit

Enter your choice : 1

Enter Employee ID : E101
Enter Name : Krisha
Enter Age : 20
Enter Salary : 50000

Employee added successfully!
How to Run the Project

Step 1:
Install Python 3 on your system.
Step 2:
Save the program file as:
Plain text
employee_management.py
Step 3:
Open terminal or command prompt.
Step 4:
Run the program using:
Bash
python employee_management.py
Assumptions
Employee IDs are entered manually.
Salary values are numeric.
User provides valid inputs.
Data is stored temporarily during program execution.
No database connectivity is used.
Advantages of the Project
Easy to understand
Beginner friendly
Demonstrates real-world OOP implementation
Reusable code structure
Simple menu-driven interface
Limitations

No file handling/database support
Data is not permanently stored
Basic console interface only
Future Enhancements
Add file handling
Add database connectivity
Create graphical user interface (GUI)
Add login authentication
Generate employee reports
Conclusion

This project successfully demonstrates the implementation of Object-Oriented Programming concepts in Python through a real-world Employee Management System.
The system provides a strong understanding of:
Inheritance
Encapsulation
Method Overriding
Constructors and Destructors
Class Relationships
It also improves problem-solving and Python programming skills.
