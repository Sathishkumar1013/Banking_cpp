# 🏦 Bank Management System

A comprehensive C++ banking system that simulates basic banking operations and ATM functionality. This system allows users to manage bank accounts, perform transactions, and use ATM services. 💼

## ✨ Features

### 🏛️ Bank Operations
- 📝 Create new bank accounts
- 👥 View account details
- 💰 Deposit money
- 💸 Transfer money between accounts

### 🏧 ATM Operations
- 💵 Withdraw money
- 💳 Check account balance
- 📥 Load money into account

## 🛠️ System Requirements

- 💻 C++ compiler (C++11 or later)
- 📁 File system access for data storage
- 🖥️ Terminal/Console for interface

## 📂 File Structure

The system uses several text files for data management:
- 🔐 `CustomerPrivateData.txt`: Stores account numbers and PINs
- 📋 `CustomerDetails.txt`: Stores customer information (name, CNIC)
- 💰 `customerBalance.txt`: Stores account balances
- 🔢 `accNumberStart.txt`: Manages account number generation

## 🚀 Installation & Setup

1. Clone or download the source code
2. Compile the code using a C++ compiler:
   ```bash
   g++ bank_system.cpp -o bank_system
   ```
3. Run the executable:
   ```bash
   ./bank_system
   ```

## 📖 Usage Guide

### 📱 Main Menu
The system presents three main options:
1. Bank
2. ATM
3. Exit

### 🏛️ Bank Services
When selecting Bank (Option 1), you can:
1. 📝 Open New Account
   - Enter first name
   - Enter last name
   - Enter CNIC
   - Set PIN
   - Initial balance of 1000 is automatically credited

2. 🔍 Account Details
   - Search by name or account number
   - View balance and personal information

3. 💰 Deposit
   - Enter account number and PIN
   - Enter amount (must be multiple of 500)

4. 💸 Transfer
   - Enter sender's account number and PIN
   - Enter recipient's account number
   - Enter amount (must be multiple of 500)

### 🏧 ATM Services
When selecting ATM (Option 2), you can:
1. 💵 Withdraw
   - Enter account number and PIN
   - Enter amount (must be multiple of 500)

2. 💳 Check Balance
   - Enter account number and PIN
   - View current balance

3. 📥 Load Money
   - Enter account number and PIN
   - Enter amount to load (must be multiple of 500)

## 🔒 Security Features

- 🔑 PIN authentication required for all transactions
- ✅ Account number verification
- 💱 Transaction amount validation
- 🗄️ Secure file storage of customer data

## ⚠️ Constraints

- 💰 All monetary transactions must be in multiples of 500
- 💵 Initial account balance is set to 1000
- 🔢 4-digit PIN required for all accounts
- 📋 CNIC required for account creation
- 🔍 Valid account numbers required for transfers

## ⚡ Error Handling

The system includes error handling for:
- ❌ Invalid account numbers
- 🚫 Incorrect PINs
- ⛔ Invalid transaction amounts
- 📁 File access errors
- 💸 Insufficient balance

## 💾 Data Persistence

All account information and transactions are stored in text files:
- 📝 Account details are saved immediately upon creation
- 📊 Transaction records are updated in real-time
- 💰 Balance updates are reflected instantly

## 🤝 Contributing

To contribute to this project:
1. 🔄 Fork the repository
2. 🌿 Create a new branch for your feature
3. ✅ Commit your changes
4. 📤 Submit a pull request

## 🚀 Future Enhancements

Potential areas for improvement:
- 🖥️ GUI implementation
- 🗃️ Database integration
- 📜 Transaction history
- 💱 Multiple currency support
- 📊 Interest calculation
- 👥 Joint account support
- 📱 Mobile banking features

## 📝 Notes

- 🔢 Keep track of your account number and PIN
- 🤫 Do not share PIN with others
- ✅ Always verify transaction details before confirming
- 💰 Ensure sufficient balance before transactions
