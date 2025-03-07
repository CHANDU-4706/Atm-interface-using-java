# ATM Java Program

## Overview
This is a simple ATM (Automated Teller Machine) simulation program written in Java. It allows users to perform basic banking operations such as withdrawing money, depositing money, and checking their account balance through a console-based interface.

## Features
- Withdraw money
- Deposit money
- Check account balance
- Input validation for transactions
- Custom error messages for insufficient balance and invalid inputs

## Prerequisites
- Java Development Kit (JDK) installed
- A Java-compatible IDE or terminal to run the program

## How to Use
1. The program will display a menu with options:
   - **1:** Withdraw Money
   - **2:** Deposit Money
   - **3:** Check Balance
   - **4:** Exit
2. Enter the corresponding number to perform the desired action.
3. Follow on-screen instructions for withdrawal or deposit.
4. Check your balance when needed.
5. Exit the program when finished.

## Code Highlights
- Uses a `Scanner` to take user input.
- Implements input validation to ensure only positive values are accepted for withdrawals and deposits.
- Prevents withdrawals exceeding the account balance.
- Runs an infinite loop to keep the ATM functional until the user chooses to exit.

## Sample Output
```
Automated Teller Machine
Choose 1 for Withdraw
Choose 2 for Deposit
Choose 3 for Check Balance
Choose 4 for EXIT
Choose the operation you want to perform: 2
Enter money to be deposited: 5000
Your Money has been successfully deposited
```

## Future Enhancements
- Implement PIN authentication for security.
- Store transaction history.
- Introduce an interface for a better user experience.

## License
This project is open-source and available for use and modification under the MIT License.

