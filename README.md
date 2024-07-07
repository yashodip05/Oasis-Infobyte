# Oasis-Task1

NAME:YASHODIP KAMBLE
Company:OASIS INFOBYTE
ID: OIB/J1/IP10794
DOMAIN:JAVA DEVELOPMENT
Duration:June to July 2024

OverView Of Project:

The ATM Interface project in Java simulates the basic functionalities of an Automated Teller Machine (ATM). This project helps in understanding object-oriented programming concepts, working with multiple classes, and managing user interactions through a console-based application. Below is a detailed overview of the project components and their functionalities:

Project Components

	1.	User Class
	•	Stores user information such as user ID, PIN, and account balance.
	•	Methods for validating PIN, retrieving account balance, and updating balance after transactions.
	2.	ATM Class
	•	Central class that manages the ATM operations.
	•	Contains methods for displaying the main menu, handling user input, and performing transactions.
	3.	Transaction Class
	•	Records the history of transactions such as deposits, withdrawals, and transfers.
	•	Maintains a list of transactions for each user.

Functionalities

	1.	User Authentication
	•	Prompts the user to enter their user ID and PIN.
	•	Validates the entered credentials against stored user data.
	2.	Main Menu
	•	Displays options for different ATM operations:
	•	View transaction history
	•	Withdraw money
	•	Deposit money
	•	Transfer money
	•	Quit
	3.	View Transaction History
	•	Displays a list of all transactions performed by the user.
	4.	Withdraw Money
	•	Prompts the user to enter the amount to withdraw.
	•	Checks if the user has sufficient balance.
	•	Updates the account balance and records the transaction.
	5.	Deposit Money
	•	Prompts the user to enter the amount to deposit.
	•	Updates the account balance and records the transaction.
	6.	Transfer Money
	•	Prompts the user to enter the recipient’s user ID and the amount to transfer.
	•	Checks if the user has sufficient balance.
	•	Updates the account balances of both the sender and the recipient and records the transaction.
	7.	Quit
	•	Exits the application.

 Key Concepts

	1.	Object-Oriented Programming (OOP):
	•	Encapsulation: User and ATM classes encapsulate data and related methods.
	•	Inheritance and Polymorphism: Not explicitly used in this simple project but could be extended.
	2.	Collections Framework:
	•	Use of ArrayList for storing transaction history.
	•	Use of HashMap for managing user data.
	3.	Error Handling:
	•	Basic error messages for invalid inputs and insufficient balance.

Extension Ideas

	1.	Graphical User Interface (GUI):
	•	Implement a GUI using JavaFX or Swing for a better user experience.
	2.	Database Integration:
	•	Store user and transaction data in a database (e.g., MySQL, SQLite).
	3.	Enhanced Security:
	•	Encrypt user PINs and use secure authentication mechanisms.
	4.	Additional Features:
	•	Add functionalities like account statement generation, multi-currency support, etc.

This project provides a foundational understanding of how ATMs function and allows for various enhancements to improve functionality and user experience.
