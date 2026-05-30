🏨 Hotel Management System (C++ OOP Project)

📌 Project Overview

The Hotel Management System is a console-based application developed in C++ using Object-Oriented Programming (OOP) principles. The system is designed to automate hotel room management operations, customer registration, room booking, billing, and checkout processes while ensuring data validation and efficient record handling.

This project demonstrates the practical implementation of core OOP concepts including Inheritance, Polymorphism, Abstraction, Encapsulation, Friend Classes, Virtual Functions, and Dynamic Memory Management.

---

🎯 Project Objectives

- Automate hotel room management operations.
- Reduce manual record-keeping errors.
- Maintain customer information securely.
- Generate bills automatically.
- Provide a structured and user-friendly hotel management solution.
- Demonstrate real-world application of Object-Oriented Programming concepts.

---

🚀 Key Features

🔐 Secure Admin Authentication

- Admin login system with limited login attempts.
- System lock after multiple failed login attempts.

🛏️ Room Management

- 10 predefined hotel rooms.
- Multiple room categories:
  - Single Room
  - Double Room
  - Deluxe Room
- Real-time room availability status.

👤 Customer Management

- Customer registration system.
- Complete customer profile storage.
- Nationality-based identification system.

✅ Input Validation

- Name validation
- Phone number validation
- Email validation
- CNIC validation for Pakistani customers
- Passport validation for international customers

📅 Smart Booking System

- Automatic booking date generation.
- Automatic day detection.
- Stay duration management.

💰 Automated Billing

- Room charges calculation.
- Service charges inclusion.
- Professional bill generation during checkout.

📊 Room Status Dashboard

- Displays:
  - Room Number
  - Room Type
  - Room Price
  - Booking Status
  - Booking Date

---

🏗️ OOP Concepts Implemented

Concept| Implementation
Encapsulation| Data members protected within classes
Inheritance| Customer inherits from Person
Abstraction| Abstract Room class
Polymorphism| Virtual functions and method overriding
Friend Class| BillGenerator accessing Hotel data
Dynamic Binding| Runtime polymorphism through Room pointers
Constructor & Destructor| Resource initialization and cleanup
Dynamic Memory Management| Room objects managed using pointers

---

📂 Class Structure

Person (Base Class)
│
└── Customer (Derived Class)

Room (Abstract Class)
│
├── SingleRoom
├── DoubleRoom
└── DeluxeRoom

Hotel
│
└── BillGenerator (Friend Class)

---

🛠️ Technologies Used

- C++
- Object-Oriented Programming (OOP)
- STL Vector
- Time Library
- Input Validation Techniques
- Dynamic Memory Allocation

---

📈 Learning Outcomes

Through this project, the following software development skills were strengthened:

- Object-Oriented Design
- Class Relationships
- Data Validation
- Runtime Polymorphism
- Memory Management
- Problem Solving
- Console Application Development
- Software Architecture Fundamentals

---

💼 Real-World Applications

This project can serve as a foundation for:

- Hotel Reservation Systems
- Hospitality Management Software
- Resort Management Applications
- Guest Information Systems
- Billing and Booking Platforms

Future enhancements may include:

- Database Integration (MySQL)
- File Handling
- Online Reservation Portal
- Employee Management Module
- Payment Gateway Integration
- GUI/Desktop Interface
- Cloud-Based Deployment

---

👨‍💻 Developer

Developed as an academic Object-Oriented Programming project to demonstrate practical implementation of software engineering concepts and real-world business problem solving using C++.

---

⭐ If you found this project useful, consider giving it a star on GitHub.
