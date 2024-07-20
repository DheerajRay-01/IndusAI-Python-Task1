# Simple Personal Budget Tracker

## Description
This Personal Budget Tracker allows users to manage their finances by recording transactions with categories "Credit" for income and "Debit" for expenses. Users can add transactions, view a summary of their total credits, debits, and net balance, and list all recorded transactions. The program supports both short forms ("C" and "D") and full forms for ease of use.

## Go to Code
[Simple Personal Budget Tracker](budgetTracker.py)

## How to Run
1. **Run the Game**:
   - Open your terminal or command prompt.
   - Navigate to the directory where `budgetTracker.py` is located.
   - Type `python budgetTracker.py` and press Enter to start.

## Example
```sh
1. Add Transaction
2. View Summary
3. View Transactions
4. Exit
Choose an option: 1
Enter amount: 120
Enter category (C for Credit / D for Debit): d
Enter description: fruits

1. Add Transaction
2. View Summary
3. View Transactions
4. Exit
Choose an option: 1
Enter amount: 300
Enter category (C for Credit / D for Debit): d
Enter description: bill

1. Add Transaction
2. View Summary
3. View Transactions
4. Exit
Choose an option: 1
Enter amount: 200
Enter category (C for Credit / D for Debit): c
Enter description: refund

1. Add Transaction
2. View Summary
3. View Transactions
4. Exit
Choose an option: 2
Total Credit: 320.0
Total Debit: 420.0
Net Balance: -100.0

1. Add Transaction
2. View Summary
3. View Transactions
4. Exit
Choose an option: 3
Date: 2024-07-20 16:02:40, Amount: 120.0, Category: Credit, Description: fruits
Date: 2024-07-20 16:02:59, Amount: 120.0, Category: Debit, Description: fruits
Date: 2024-07-20 16:03:12, Amount: 300.0, Category: Debit, Description: bill
Date: 2024-07-20 16:03:30, Amount: 200.0, Category: Credit, Description: refund

1. Add Transaction
2. View Summary
3. View Transactions
4. Exit
Choose an option: 4
```