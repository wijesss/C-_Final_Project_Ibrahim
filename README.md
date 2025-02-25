# C-_Final_Project_Ibrahim

Banking System in C++ (Console-Based)

Overview

This is a console-based Banking System implemented in C++. 
It allows users to:
•	Register an account
•	Login
•	Deposit money
•	Withdraw money
•	Check balance
•	View transaction history
This version is designed for VS Code and uses file storage to persist user data and transaction history.

Features

•	User Registration & Login: Securely create and access accounts.
•	Deposit & Withdraw: Manage funds with simple commands.
•	Check Balance: Displays the current balance.
•	Transaction History: View a history of deposits and withdrawals.
•	File-Based Storage: Saves account details and transactions for persistence.

How to Run in VS Code

1.	Install Visual Studio Code and C++ extensions.
2.	Ensure you have a C++ compiler (MinGW for Windows, g++ for Linux/macOS).
3.	Clone or copy the project files into a folder.
4.	Open VS Code and navigate to the project folder.
5.	Open a terminal and compile the code: g++ banking_system.cpp -o banking_system
6.	Run the compiled program: ./banking_system
7.	Follow on-screen instructions to register, log in, and manage accounts.

Notes

•	User data and transactions are stored in text files.
•	Ensure you have write permissions in the project directory.
•	If files are missing, the program will create them automatically.

Future Improvements
•	Add password encryption for security.
•	Implement admin functionality to manage user accounts.
•	Use a database instead of text files for better scalability.
•	Develop safety measurements (e.g, implementing 2FA.)

