# BankingSystem
# 🏦 Simple Banking System in Java

This is a **console-based banking application** developed using Java. It allows users to create a bank account, deposit funds, withdraw money with sufficient balance check, and view current balance — all while demonstrating core Java concepts like object-oriented programming and exception handling.

---

## 💡 Features

- ✅ Create a new bank account
- 💰 Deposit money (only positive amounts)
- 💸 Withdraw money (with insufficient balance validation)
- 💼 Check current balance
- ⚠️ Handles invalid inputs using exceptions
- 📟 Menu-driven interface for easy use

---

## 🧑‍💻 Technologies Used

- Java SE (Standard Edition)
- Object-Oriented Programming (OOP)
- Custom and Built-in Exception Handling
- Java Scanner for user input

---

## 📁 Project Structure
- `InsufficientFundsException`: Custom exception for withdrawal errors  
- `BankAccount`: Class handling account data and operations  
- `BankingSystem`: Main class with menu and execution logic

---

## 🚀 How to Run

1. **Open terminal or command prompt**

2. **Compile the Java program**
   javac BankingSystem.java
3. **Run the program**
   java BankingSystem

## Sample Output 
=== Welcome to Simple Banking System ===
Enter Account Holder Name: John Doe
Enter Account Number: 123456789
Account created successfully.


--- Banking Menu ---
1. Deposit
2. Withdraw
3. Check Balance
4. Exit
Enter your choice (1-4): 1
Enter amount to deposit: 5000
Deposited: $5000.00

--- Banking Menu ---
1. Deposit
2. Withdraw
3. Check Balance
4. Exit
Enter your choice (1-4): 3
Current Balance: $5000.00

--- Banking Menu ---
1. Deposit
2. Withdraw
3. Check Balance
4. Exit
Enter your choice (1-4): 2
Enter amount to withdraw: 2000
Withdrawn: $2000.00

--- Banking Menu ---
1. Deposit
2. Withdraw
3. Check Balance
4. Exit
Enter your choice (1-4): 3
Current Balance: $3000.00

--- Banking Menu ---
1. Deposit
2. Withdraw
3. Check Balance
4. Exit
Enter your choice (1-4): 2
Enter amount to withdraw: 5000
Error: Insufficient balance. Withdrawal failed.

--- Banking Menu ---
1. Deposit
2. Withdraw
3. Check Balance
4. Exit
Enter your choice (1-4): 1
Enter amount to deposit: -100
Error: Deposit amount must be positive.

--- Banking Menu ---
1. Deposit
2. Withdraw
3. Check Balance
4. Exit
Enter your choice (1-4): 4
Thank you for using the banking system!

✅ Validations & Exception Handling
Deposit and withdrawal amounts must be greater than 0
Custom InsufficientFundsException for low balance
InputMismatchException for invalid input types
IllegalArgumentException for empty names and numbers

