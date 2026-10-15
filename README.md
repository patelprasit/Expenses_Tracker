Expense Tracker 💰
About the Project

Expense Tracker is a simple C++ program that helps you manage your daily expenses. You can record your spending, view all your expenses, search for specific transactions, and generate reports to understand where your money goes.

This project is useful for learning C++ programming, file handling, and basic data management.

Features
Add Expense: Add a new expense with its amount, date, category, description, and payment method.
View All Expenses: See all your recorded expenses and the total amount spent.
Search Expenses: Find expenses by date, category, description, or payment method.
Category-wise Report: View how much money you spend in each category and its percentage of total spending.
Monthly Report: View your expenses for a specific month.
Delete Expense: Remove an expense using its unique ID.
Save Data: Store expense records in a text file so they can be used again later.
Input Validation: Handle invalid inputs and incorrect expense amounts.
Technologies Used
Programming Language: C++
File Handling: Text files
Standard Libraries: iostream, fstream, string, vector, algorithm, and other C++ libraries
Project Structure
Expenses_Tracker/
│
├── expenses_tracker.cpp   # Main C++ source code
├── expenses.txt           # Stores expense records
├── expenses_tracker.exe   # Compiled application for Windows
└── README.md              # Project documentation

How to Run the Project
Requirements
A C++ compiler, such as GCC (g++) or MinGW.
A terminal or command prompt.
Step 1: Clone the Repository

Open your terminal and run:

git clone https://github.com/patelprasit/Expenses_Tracker.git

Step 2: Open the Project Folder
cd Expenses_Tracker

Step 3: Compile the Program

If you have GCC installed, run:

g++ expenses_tracker.cpp -o expenses_tracker

Step 4: Run the Program

On Windows:

expenses_tracker.exe


On Linux or macOS:

./expenses_tracker

How to Use

After running the program, you will see a menu like this:

============================================================
 EXPENSE TRACKER
 PERSONAL FINANCE MANAGER
============================================================
 1. Add Expense
 2. View All Expenses
 3. Search Expenses
 4. Category-wise Report
 5. Monthly Report
 6. Delete Expense
 0. Exit
============================================================


Enter the number for the action you want to perform.

Example: Adding an Expense

When you select 1. Add Expense, enter the requested details:

Amount: 250
Date: 2026-10-15
Category: Food
Description: Lunch
Payment Method: UPI

The program saves the expense and assigns it a unique ID.

Note: The amount should be greater than zero, and the date should use the YYYY-MM-DD format.

Expense Categories

You can organize your expenses using categories such as:

Food
Travel
Shopping
Bills
Education
Health
Other

You can also enter your preferred category.

Data Storage

All expense records are stored in the expenses.txt file.

Each record contains the following information:

Expense ID
Amount
Date
Category
Description
Payment method

The program reads this file when displaying expenses and generating reports. Keep the file in the program's working directory so your saved records remain available.

Future Improvements

Some features that could be added in the future are:

Edit existing expenses.
Set monthly budgets.
Track income and savings.
Export reports to CSV or Excel.
Add a graphical user interface.
Show charts for spending patterns.
Contributing

Contributions are welcome!

Fork this repository.
Create a new branch.
Make your changes.
Commit and push your changes.
Open a pull request.
License

No license has been specified yet. Please add a suitable license file if you want others to reuse, modify, or distribute this project under defined terms.

Made with ❤️ using C++.
