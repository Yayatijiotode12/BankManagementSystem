📌 Overview

This project is a console-based Bank Management System developed in C++ to simulate common banking operations. It demonstrates the practical use of Object-Oriented Programming (OOP) and binary file handling for managing persistent customer data.

The system allows users to create and manage bank accounts, perform transactions, and maintain records stored in a binary file.

✨ Features

Create new bank accounts with validation

Deposit and withdraw money

Balance enquiry for specific accounts

Modify existing account details

Delete bank accounts

Display all account holder records

Persistent storage using binary files

🧠 Concepts & Technologies Used

C++ Programming

Object-Oriented Programming (Classes & Encapsulation)

Binary File Handling (ifstream, ofstream, fstream)

File Pointer Manipulation (seekp, seekg)

Menu-Driven Program Design

Input Validation and Formatted Output

🗂️ Project Structure
├── main.cpp          // Source code
├── account.dat       // Binary data file (generated at runtime)
└── README.md

⚙️ How the System Works

Each bank account is represented as an object of the account class.

Account records are written directly to a binary file (account.dat).

Record modification is handled by moving the file pointer backward using seekp() and overwriting the existing record.

Account deletion is performed using a temporary file approach to rewrite all records except the deleted one.

▶️ How to Compile and Run

Compile the program:

g++ main.cpp -o bank


Run the executable:

./bank


Use the on-screen menu to perform banking operations.

📋 Supported Operations

New Account Creation

Deposit Amount

Withdraw Amount (with minimum balance check)

Balance Enquiry

Modify Account

Delete Account

Display All Accounts

🚀 Future Enhancements

Enforce unique account numbers

Add password-based authentication

Implement interest calculation

Improve error handling

Add GUI or database integration

👨‍💻 Author

Yayati Jiotode

⭐ Why This Project?

This project showcases real-world application of C++ file handling and OOP concepts, commonly evaluated in technical interviews and academic assessments.
