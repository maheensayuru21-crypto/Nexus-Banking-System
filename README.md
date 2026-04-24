# Simple Banking Application (Java)

A console-based banking system built with core Java, focusing on **Object-Oriented Programming (OOP)** and **Data Persistence**.

## 🚀 Features
- **User Registration:** Dynamically generate unique 4-digit account numbers.
- **Secure Login:** Session-based access to specific account data.
- **Stateful Transactions:** Deposit and withdraw funds with real-time balance updates.
- **Data Persistence:** All account information is saved to a local flat-file database (`accounts.txt`).
- **Error Handling:** Robust validation for numeric inputs and insufficient funds.

## 🛠️ Technical Stack
- **Language:** Java 17+
- **Data Structure:** `HashMap` for O(1) account lookups.
- **Storage:** File I/O (CSV-style parsing).
- **Version Control:** Git/GitHub with Feature-Branch workflow.

## 📖 What I Learned (Backend Focus)
- **Separation of Concerns:** Split logic into Model (`Account`), Controller (`BankingApp`), and Data Access (`FileHandler`).
- **Encapsulation:** Used private fields and public getters to protect sensitive financial data.
- **Defensive Programming:** Implemented `try-catch` blocks to handle malformed user input.



## 🖥️ Project Demo

Below is an example of a typical user session, from registration to performing a transaction.

### 1. Registration
===== MAIN MENU =====
1. Login to Existing Account
2. Register New Account
3. Exit
Choice: 2

Enter Account Holder Name: Jon Johns
Enter Initial Deposit: 1000

SUCCESS! Account created.
Your Account Number is: 5482


### 2. Login and transaction
===== MAIN MENU =====
1. Login to Existing Account
2. Register New Account
3. Exit
Choice: 1

Enter Account Number: 5482
Login Successful! Welcome, Jon Johns!

--- Dashboard (5482) ---
1. View Balance
2. Deposit
3. Withdraw
4. Logout
Choice: 3

Enter withdrawal amount: 250
Withdrawn: $250.0
Transaction saved to ledger.