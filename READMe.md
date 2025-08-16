# Bank Project 2.0

A simple **Banking System in C++** that manages clients and users with file-based storage.  
The project simulates an ATM for customers and an admin system for managing users and accounts.

---

## Features

- 👤 **Client Features:**
  - Withdraw (fast or custom amounts)
  - Deposit
  - Check balance

- 🔑 **Admin Features:**
  - Manage customers (Add, Update, Delete, Search, List)
  - Manage users with permissions
  - View total balances
  - File-based persistence (`custumers.txt`, `Users.txt`)

---

## Files

- `bankproject2.0.cpp` → main source code
- `custumers.txt` → customer database
- `Users.txt` → system users database

---
## How to Run

1. Open a terminal or command prompt.
2. Navigate to the folder containing `bankproject2.0.cpp`.
3. Compile and run the program:
   - On Linux/macOS:
     ```bash
     g++ bankproject2.0.cpp -o BankSystem
     ./BankSystem
     ```
   - On Windows:
     ```bash
     g++ bankproject2.0.cpp -o BankSystem
     BankSystem.exe
     ```
