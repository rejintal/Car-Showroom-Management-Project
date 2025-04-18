Showroom Management System
Overview
This Showroom Management System is a Java-based console application that helps manage automotive showrooms, employees, and car inventory. This system provides a simple yet effective way to add and view information about showrooms, staff members, and vehicles in stock.
Features

Showroom Management: Add new showrooms with details like name, address, manager information, employee count, and current vehicle inventory.
Employee Management: Register employees with unique IDs (automatically generated UUIDs), names, ages, departments, and assigned showrooms.
Car Inventory Management: Add cars to the inventory with comprehensive details including name, color, fuel type, price, car type (sedan/SUV/hatchback), and transmission type.
Information Retrieval: View complete details of all registered showrooms, employees, and cars in the system.

Project Structure

Main.java: Contains the main program logic, menu system, and program flow control.
Showroom.java: Defines the Showroom class with attributes and methods for managing showroom details.
Employees.java: Implements the Employees class that extends Showroom and includes employee-specific attributes and methods.
Cars.java: Implements the Cars class that extends Showroom with car-specific attributes and methods.
utility interface: Defines common methods (get_details() and set_details()) implemented by all classes.

Technical Implementation

Object-Oriented Design: Utilizes inheritance with the Showroom as the parent class and Employees and Cars as child classes.
Interface Implementation: All classes implement the utility interface to ensure consistent method implementations.
Data Collection: Uses Java's Scanner class to collect user input for all entity attributes.
Unique Identifiers: Generates unique IDs for employees using Java's UUID class.
Menu-Driven Interface: Features an intuitive console menu system for easy navigation and operation.

How to Use

Run the Main.java file to start the application
Use the main menu to select operations:

Options 1-3: Add new showrooms, employees, or cars
Options 4-6: View details of all showrooms, employees, or cars
Enter 0 to exit the application


Follow the prompts to enter required information for each entity
Navigate back to the main menu after completing operations

Future Enhancements

Data persistence using file I/O or database integration
Search functionality to find specific showrooms, employees, or cars
Update and delete operations for existing records
User authentication and role-based access control
Enhanced UI with graphical components

Requirements

Java Development Kit (JDK) 8 or higher
Command-line interface or IDE for Java development
