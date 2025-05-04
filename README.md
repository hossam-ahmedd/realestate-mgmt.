# Project Report: Real Estate Management System

## Introduction
This project aims to develop a software system that assists employees in real estate companies in managing real estate-related operations such as sales, rentals, payments, and managing staff and clients. The system was implemented using the Java programming language and features a simple interface that enables users to perform their daily tasks efficiently.

## Home Page
After logging in, the employee is directed to the home page, which contains a set of panels or buttons—each representing a specific function in the system. This interface allows users to quickly access core features like adding sales or rentals, and managing properties and clients.

## Main Features

1. **Property Management**  
   This feature allows employees to add new properties to the system or delete unavailable ones. The database is automatically updated according to the user’s operations.

2. **Add Sale**  
   Through this page, employees can register new property sales. The system first checks the property’s availability for sale. If it’s not available, an alert message is shown to the user.

3. **Add Rental**  
   Allows employees to register new rental contracts for specific properties. The system checks the availability of the property for the selected time period. If unavailable, a notification is shown.

4. **Payments and Sales**  
   All completed operations (sales or rentals) are listed on this page along with their associated payment details. A full report of received payments and transactions is displayed, retrieved from the system’s database.

5. **Manage Staff or Clients**  
   This feature is reserved for users with administrative privileges. It allows them to add or remove employees and clients as needed by the company.

## Technologies Used
- **Programming Language:** Java  
- **Development Environment:** NetBeans 17 
- **Database:** MySQL  
- **Framework:** Swing

## Challenges Faced
- Verifying property availability during specific dates required accurate SQL queries.  
- Designing a user-friendly interface suitable for employees with various technical levels.

## Conclusion
This system offers an integrated solution for managing real estate companies in an efficient and organized way. It simplifies the workflow for employees by automating many processes and provides tools for managing and analyzing data.
