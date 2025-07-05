# Banking_system
## Overview
The provided Python file implements a simple banking system using object-oriented programming principles. It allows users to create a bank account, deposit money, withdraw money, and check their account balance.

## Features
* Account Creation: Users can create a bank account by providing their name.
  
* Deposit Functionality: Users can deposit a positive amount into their account.
  
* Withdrawal Functionality: Users can withdraw money from their account, provided they have sufficient balance.
  
* Balance Inquiry: Users can check their current account balance.
  
# Class Structure
## BankAccount
## Attributes:
* account_holder: The name of the account holder.
* balance: The current balance of the account (default is 0).
## Methods:

* __init__(self, account_holder, balance=0): Initializes the account with the holder's name and an optional balance.
* deposit(self, amount): Adds the specified amount to the account balance if the amount is positive.
* withdraw(self, amount): Deducts the specified amount from the account balance if sufficient funds are available.
* check_balance(self): Displays the account holder's name and current balance.
## Example Usage
The main function provides a user interface for interacting with the banking system. It prompts the user to:

1. Enter their name to create an account.
2. Choose from the following options:
   
Deposit money
Withdraw money
Check balance
Exit the application
