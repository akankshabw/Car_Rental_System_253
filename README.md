# CS253_Assignment_1 : Car Rental System

This is the assigment 1 of CS253 that implements a car rental system in C++ using Object Oriented Programming paradigms. The code is present in "main.cpp". There are 3 kinds of users which are customers, employees and manager. They have different functionalities and specifications. These details are mentioned in the "Assignment". All the required functionalities of the assignment have been implemented accordingly.

There are 4 main databases of this system.
1. "cars.csv" stores the details of each car available in this system.One row stores details of one car[Id,Model Name,Condition,Due Date,Rental Price,Status,Rented by(if rented)].
2. "Customer.csv" stores the details of each customer. One row stores details of one customer[Id,Name,password,Fine Due,Record,Mobile,Status].
3. "Employee.csv" stores the details of each employee.One row stores details of one customer[Id,Name,password,Fine Due,Record,Mobile,Status].
4. "Manager.csv" stores the details of manager. One row stores details of one customer[Id,Name,password,Mobile].

There are another csv files each corresponding to the cars rented by some customer or employee.

To run the system, type the following commands in the console:

g++ main.cpp -o main
.\main

The system will run on the console. The data modified throughout the program run will be reflected in the csv files.
