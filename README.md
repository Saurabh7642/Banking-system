# Banking-system
This project is a simple command-line banking system built in C++ that allows users to manage bank accounts. It demonstrates basic operations like creating accounts, depositing and withdrawing funds, balance inquiries, and closing accounts. The account data is persisted using file handling for storage, allowing for data persistence across sessions.

Features
Open Account: Create a new bank account with a unique account number, first name, last name, and an initial balance.
Deposit Funds: Deposit money into an existing account.
Withdraw Funds: Withdraw money from an account, with a check to ensure the balance does not go below a minimum threshold.
Balance Inquiry: Check the current balance and account details of an existing account.
Close Account: Delete an account from the system.
Show All Accounts: Display details of all accounts currently in the system.
Technology Used
C++ Standard Library:
iostream for input and output operations.
fstream for file handling to persist account data.
map to manage a collection of accounts for quick lookups by account number.
Basic exception handling for errors like insufficient funds.
