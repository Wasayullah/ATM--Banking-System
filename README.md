# 🏦 ATM Banking System

A beginner-friendly **ATM Banking System** built with **Python** in **Jupyter Notebook**.

This project simulates the basic operations of an ATM, including PIN authentication, checking balance, depositing money, withdrawing money, changing the PIN, and viewing transaction history.

---

## 📌 Project Overview

The **ATM Banking System** is a console-based Python project designed to practice fundamental programming concepts.

The user first authenticates using a 4-digit PIN. After successful authentication, an interactive ATM menu is displayed.

The user can then perform different banking operations until they choose to exit.

This project is part of my journey of learning **Python and AI & Data Science**.

---

## ✨ Features

- 🔐 4-digit PIN authentication
- 🚫 Maximum 3 incorrect PIN attempts
- 💰 Check account balance
- 💵 Deposit money
- 💸 Withdraw money
- 🔑 Change PIN
- 📜 View transaction history
- 🛡️ Basic input validation
- ⚠️ Handles invalid numerical input
- 🚫 Prevents withdrawal when balance is insufficient
- 🔄 Interactive ATM menu
- 📊 Final account summary

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Jupyter Notebook | Development and execution environment |

### Python Concepts Used

- Variables
- Data types
- Strings
- Lists
- Functions
- `if / elif / else`
- `while` loops
- `for` loops
- `input()`
- `print()`
- String methods
- `try / except`
- Basic validation
- Global variables
- Formatted strings

---

## 📂 Project Structure

```text
ATM-Banking-System/
│
├── ATM_Banking_System.ipynb
│
└── README.md
```

---

## ⚙️ How It Works

### 1. PIN Authentication

The system asks the user to enter their PIN.

The user gets a maximum of **3 attempts**.

```text
Enter your 4-digit PIN: 1234

Login successful!
```

If the PIN is incorrect three times:

```text
Too many incorrect attempts.
Your account has been temporarily locked.
```

---

### 2. ATM Menu

After successful authentication, the main menu appears:

```text
========== ATM SYSTEM ==========

1. Check Balance
2. Deposit Money
3. Withdraw Money
4. Change PIN
5. Transaction History
6. Exit
```

The user can select an operation by entering its number.

---

## 💰 Check Balance

The balance option displays the current account balance.

Example:

```text
========== BALANCE ==========

Current Balance: Rs. 10000

=============================
```

---

## 💵 Deposit Money

The user can add money to the account.

Example:

```text
Enter deposit amount: 5000

Rs. 5000.00 deposited successfully.
Current Balance: Rs. 15000.00
```

The transaction is also saved in the transaction history.

---

## 💸 Withdraw Money

The user can withdraw money from their account.

Example:

```text
Enter withdrawal amount: 2000

Rs. 2000.00 withdrawn successfully.
Remaining Balance: Rs. 13000.00
```

The system also checks whether the account has enough balance.

If the withdrawal amount is greater than the balance:

```text
Insufficient balance.
Available Balance: Rs. 13000.00
```

---

## 🔑 Change PIN

The user can change their existing PIN.

The system first verifies the current PIN.

The new PIN must:

- Contain exactly 4 digits
- Contain numbers only
- Be different from the old PIN

Example:

```text
Enter your current PIN: 1234
Enter your new 4-digit PIN: 5678

PIN changed successfully!
```

---

## 📜 Transaction History

The system records deposits and withdrawals during the current program session.

Example:

```text
====== TRANSACTION HISTORY ======

1. Deposit: Rs. 5000.00
2. Withdrawal: Rs. 2000.00
3. Deposit: Rs. 1000.00

=================================
```

---

## 🛡️ Input Validation

The program includes basic validation to prevent invalid operations.

For example, the user cannot deposit a negative amount:

```text
Enter deposit amount: -500

Please enter an amount greater than 0.
```

It also handles non-numeric input:

```text
Enter deposit amount: abc

Invalid amount. Please enter a number.
```

---

## 🧮 Initial Account

For demonstration purposes, the program starts with:

```text
Initial PIN: 1234
Initial Balance: Rs. 10,000
```

> **Note:** This is a learning project. The PIN and account data are stored directly in the Python program and are not suitable for a real banking system.

---

## 🚀 How to Run

### Step 1 — Install Python

Download and install Python if it is not already installed.

### Step 2 — Install Jupyter Notebook

You can install Jupyter using:

```bash
pip install notebook
```

### Step 3 — Open Jupyter Notebook

Run:

```bash
jupyter notebook
```

### Step 4 — Open the Project

Open:

```text
ATM_Banking_System.ipynb
```

### Step 5 — Run the Cells

Run the notebook cells from top to bottom.

In Jupyter Notebook:

```text
Cell → Run All
```

---

## 🧪 Example Session

```text
Enter your 4-digit PIN: 1234

Login successful!

========== ATM SYSTEM ==========

1. Check Balance
2. Deposit Money
3. Withdraw Money
4. Change PIN
5. Transaction History
6. Exit

Enter your choice: 2

Enter deposit amount: 5000

Rs. 5000.00 deposited successfully.
Current Balance: Rs. 15000.00
```

Then:

```text
Enter your choice: 3

Enter withdrawal amount: 2000

Rs. 2000.00 withdrawn successfully.
Remaining Balance: Rs. 13000.00
```

Transaction history:

```text
====== TRANSACTION HISTORY ======

1. Deposit: Rs. 5000.00
2. Withdrawal: Rs. 2000.00

=================================
```

---

## 🧠 What I Learned

Through this project, I practiced:

- How to create reusable Python functions
- How to use loops for interactive programs
- How to validate user input
- How to work with lists
- How to store transaction data
- How to use conditional statements
- How to handle errors using `try / except`
- How to build a menu-driven application
- How to organize a Python project in Jupyter Notebook

---

## 🔮 Future Improvements

Possible improvements for future versions:

- 👤 Multiple user accounts
- 💾 Save data to a JSON file
- 🗄️ Use SQLite/MySQL database
- 🔐 Hash passwords/PINs instead of storing them as plain text
- 🧾 Generate transaction receipts
- 📅 Add transaction dates and times
- 💳 Add account numbers
- 📱 Build a graphical user interface
- 🌐 Convert it into a web application
- 📊 Add transaction analytics
- 🔒 Add better authentication and security

---

## 🎯 Learning Roadmap

This project is part of my Python learning journey:

```text
Python Basics
     ↓
Student Performance Analyzer
     ↓
Personal Expense Analyzer
     ↓
ATM Banking System
     ↓
NumPy
     ↓
Pandas
     ↓
Matplotlib
     ↓
Data Analysis
     ↓
Machine Learning
     ↓
AI & Data Science Projects
```

---

## ⚠️ Disclaimer

This project is created **for educational purposes only**.

It is a simulation of an ATM and does **not** connect to any real bank, payment system, or financial institution.

The authentication and account storage methods used in this project are intentionally simple because the goal is to practice Python programming concepts.

---

## 👨‍💻 Author

**Mohammad Wasayullah**

Aspiring Web Developer | Python Learner | AI & Data Science Student

### GitHub

**Wasayullah**

---

## ⭐ Support

If you found this project useful for learning Python, consider giving the repository a ⭐ on GitHub.

---

## 📄 License

This project is available for educational and personal learning purposes.