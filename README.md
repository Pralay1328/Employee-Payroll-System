
*Employee Payroll System*

Welcome to the Employee Payroll System! This Java project demonstrates the concepts of Object-Oriented Programming (OOP) by providing a simple payroll management system for employees. The system allows you to add, remove, and display employees while calculating their salaries.

Features
1. Add Employees: Add new employees to the system. The system supports both full-time and part-time employees.
2. Calculate Salary: Calculate the salary of employees based on their employment type (full-time or part-time).
3. Remove Employees: Remove employees from the system using their ID.
4. Display Employees: Display the details of all employees, including their calculated salary.

OOP Concepts Used
1. Class: The project uses classes (Employee, FullTimeEmployee, and PartTimeEmployee) to represent different types of employees.
2. Object: Objects are instances of classes, such as full-time and part-time employee objects.
3. Encapsulation: The project uses encapsulation to hide the internal details of classes (e.g., employee attributes).
4. Inheritance: The FullTimeEmployee and PartTimeEmployee classes inherit from the abstract Employee class.
5. Polymorphism: The calculateSalary method is overridden in the subclasses (FullTimeEmployee and PartTimeEmployee) to provide specific implementations for different employee types.

Code Structure
 
 Employee: An abstract class representing an employee with properties such as name and id. It also includes an abstract method calculateSalary().
 
 FullTimeEmployee: A subclass of Employee representing full-time employees with a monthly salary.
 
 PartTimeEmployee: A subclass of Employee representing part-time employees with hourly wage and hours worked.
 
 PayrollSystem: Manages the list of employees and provides methods to add, remove, and display employees.

 Main: Contains the main method that demonstrates the functionality of the system.


