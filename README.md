# Banking System – Mini Project

A Python-based mini project that simulates basic banking operations through a
simple menu-driven console application.

## Features

- 🏦 Create a bank account (name, phone number, PIN)
- 🔐 Login using Account Number & PIN
- 💰 Check account balance
- ➕ Deposit money
- ➖ Withdraw money
- 🔁 Transfer money between accounts
- 📜 View transaction history
- 🔑 Change PIN
- 🚪 Logout

## Python Concepts Used

- Variables & Data Types
- Conditional Statements
- Loops
- Functions
- Lists & Dictionaries
- String Operations
- Modules (`random`, `datetime`)

## Project Structure

```
CREATE ACCOUNT
      ↓
Account Number + PIN
      ↓
    LOGIN
      ↓
┌─────────────────────────┐
│      ACCOUNT MENU       │
├─────────────────────────┤
│ 1. Check Balance        │
│ 2. Deposit              │
│ 3. Withdraw             │
│ 4. Transfer             │
│ 5. Transaction History  │
│ 6. Change PIN           │
│ 7. Logout               │
└─────────────────────────┘
      ↓
    LOGOUT
      ↓
  MAIN MENU
```

## How to Run

Requires Python 3.

```bash
python3 banking_system.py
```

Then follow the on-screen menu:

1. Choose **1** to create a new account — you'll get a generated 6-digit
   account number. Save it.
2. Choose **2** to log in with that account number and your PIN.
3. Use the account menu to deposit, withdraw, transfer, view history,
   change your PIN, or log out.

## Notes

- Data is stored **in memory only** (a Python dictionary) — accounts and
  transactions reset each time you restart the program. This keeps the
  project focused on core Python concepts rather than file/database
  persistence.
- Account numbers are randomly generated 6-digit numbers.
- Transaction history is timestamped using the `datetime` module.

## Project Objective

This project combines core Python concepts into one real-world application,
demonstrating how account management, transactions, authentication, and
transaction records work together in a simplified banking system.
