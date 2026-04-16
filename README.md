# Java Bank Account System

This Java project models a basic bank account system using object-oriented programming principles. It includes a base `BankAccount` class and a derived `CheckingAccount` class that supports overdraft handling and interest rates.

## Features

- Class design and inheritance
- Encapsulation through fields and methods
- Transaction processing with deposits and withdrawals
- Overdraft logic with a fixed fee
- Formatted console output for account summaries

## Concepts Demonstrated
- Object-Oriented Programming (OOP)
- Inheritance
- Encapsulation
- Conditional logic

## Technologies Used
- Java
- JDK 11+
- Any Java IDE

## Project Structure
- `BankAccount.java` – Base account class
- `CheckingAccount.java` – Extended account with overdraft logic
- `BankAccountTest.java` – Main test program

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

## What I Learned
This project strengthened my understanding of inheritance and how to extend base classes to add new behavior. I also learned how to implement real-world logic such as overdraft handling using conditional statements.

## Future Improvements
- Add savings account support
- Add input validation
- Add unit tests
- Store data using files or a database

## Screenshots

![BankAccount1](Screenshots/BankAccount1.png)
![BankAccount2](Screenshots/BankAccount2.png)

![CheckingAccount](Screenshots/CheckingAccount.png)
![CheckingAccount2](Screenshots/CheckingAccount2.png)


![Output](Screenshots/Output.png)



