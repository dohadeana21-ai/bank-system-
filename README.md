# 🏦 Bank Management System

A simple **Bank Management System** built using **C++** and **Object-Oriented Programming (OOP)**.

This project simulates basic banking operations, allowing users to deposit money, withdraw money, and check their current account balance through an interactive console menu.

---

## ✨ Features

- 💳 **Account Creation:** Initialize an account with a name and starting balance.
- 💰 **Deposit:** Add money to the account.
- 💸 **Withdraw:** Withdraw money from the account.
- 📊 **Check Balance:** Display the current account balance.
- 🛡️ **Input Validation:** Prevent invalid deposit and withdrawal amounts.
- ⚠️ **Insufficient Funds Check:** Prevent withdrawals that exceed the available balance.
- 🎨 **Colored Console Output:** Display success and error messages in different colors.

---

## 🧱 Class Structure

### Account Class

Responsible for managing the bank account information and operations.

**Private Attributes:**
- `name`: Stores the account holder's name.
- `balance`: Stores the current account balance.

**Public Methods:**
- `Account()`: Constructor that initializes the account.
- `deposit()`: Adds money to the account.
- `withdraw()`: Withdraws money if sufficient funds are available.
- `checkBalance()`: Displays the current balance.

---

## 🛠️ Concepts Used

- C++
- Object-Oriented Programming (OOP)
- Classes & Objects
- Constructors
- Encapsulation
- Private & Public Access Specifiers
- Member Functions
- Conditional Statements
- While Loop
- Functions
- Input Validation

---

## 📋 Program Menu

| Option | Operation |
|:---:|---|
| 1 | Deposit |
| 2 | Withdraw |
| 3 | Check Balance |
| 4 | Exit |

---

## 🚀 How to Run

1. Clone or download the repository.
2. Open the project using a C++ IDE such as Code::Blocks.
3. Compile and run the program.
4. Choose an option from the menu to perform a banking operation.

---

## 📌 Notes

- The program currently supports one bank account.
- Account information is stored in memory and is not saved permanently.
- Uses `windows.h` for
