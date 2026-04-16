# Java Bank Account System

## Overview

This Java project models a basic bank account system using object-oriented programming principles. It includes a base `BankAccount` class and a derived `CheckingAccount` class that supports overdraft handling and interest rates.

This project was built to demonstrate:

- Class design and inheritance
- Encapsulation through fields and methods
- Transaction processing with deposits and withdrawals
- Overdraft logic with a fixed fee
- Formatted console output for account summaries

## Project Structure

- `BankAccount.java` – Defines the base bank account with deposit, withdrawal, getters/setters, and account summary methods.
- `CheckingAccount.java` – Extends `BankAccount`, adds an interest rate, and applies a `$30` fee when an overdraft occurs.
- `BankAccountTest.java` – Contains the `main` method used to test account creation and account transactions.


## Features

- Create a bank account with owner details and account ID
- Deposit money into an account
- Withdraw money from an account
- Apply overdraft behavior in a checking account
- Display formatted account information
- Demonstrate inheritance in Java

## Technologies Used

- Java
- Object-Oriented Programming (OOP)
- Visual Studio Code or any Java IDE
- JDK 11 or higher

## How to Run

### Prerequisites
- Java Development Kit (JDK 11+)
- Visual Studio Code, IntelliJ IDEA, Eclipse, or another Java IDE

### Steps
1. Clone or download this repository.
2. Open the project in your IDE.
3. Navigate to the `src` folder.
4. Compile the Java files.
5. Run `BankAccountTest.java`.

```bash
javac BankAccount.java CheckingAccount.java BankAccountTest.java
java BankAccountTest
```

## Example Output

```text
Initial deposit of $500.00

Account Summary:
Name: Alice Ramirez
Account ID: 12345
Balance: $500.00
Interest Rate: 1.25%

Withdrawing $600.00 (should trigger overdraft)
Overdraft! A $30 fee has been applied.

Account Summary:
Name: Alice Ramirez
Account ID: 12345
Balance: -$30.00
Interest Rate: 1.25%

Depositing $200.00

Account Summary:
Name: Alice Ramirez
Account ID: 12345
Balance: $170.00
Interest Rate: 1.25%
```

## Concepts Demonstrated
This project demonstrates object-oriented design in Java by using inheritance to extend a base bank account into a checking account with additional behavior. It also shows how transaction rules can be enforced through methods and conditional logic instead of relying on built-in shortcuts.

## Future Improvements
- Add savings account support
- Add input validation for account creation
- Add unit tests
- Store account data using files or a database
- Build a simple GUI version

## Screenshots

![BankAccount1](Screenshots/BankAccount1.png)
![BankAccount2](Screenshots/BankAccount2.png)

![CheckingAccount](Screenshots/CheckingAccount.png)
![CheckingAccount2](Screenshots/CheckingAccount2.png)


![Output](Screenshots/Output.png)



