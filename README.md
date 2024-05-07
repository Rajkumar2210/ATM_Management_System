# ATM_Management_System

### ATM Management System

This is a simple ATM management system implemented in Java. The system allows users to perform basic banking operations like checking balance, depositing money, and withdrawing money after entering a valid PIN.

### Features

- **PIN Verification**: Users are required to enter a valid PIN to access their account. If the PIN is incorrect or not present, they are prompted to create an account.
- **Account Creation**: Users can create an account by setting a PIN code. The PIN should be between 1000 and 99999.
- **Menu Options**: Once logged in, users can choose from a menu of options including checking balance, withdrawing money, depositing money, and exiting.
- **Balances**: The system keeps track of account balances and updates them accordingly after withdrawals and deposits.
- **Error Handling**: The system provides error messages for invalid PINs, insufficient balances, and incorrect menu choices.

### How to Use

1. **Compile**: Compile the Java file `ATM.java`.
   ```bash
   javac ATM.java
   ```

2. **Run**: Run the compiled class file.
   ```bash
   java ATM
   ```

3. **Follow Instructions**: Follow the prompts to perform various banking operations. Enter the PIN to access an existing account or create a new one if necessary.

### Requirements

- Java Development Kit (JDK) installed on your system.
- Command-line interface (Terminal, Command Prompt, etc.) to compile and run the Java program.

### Note

- This is a basic ATM management system and does not include advanced features like account management, transaction history, or user authentication.
- PINs are stored in memory using a `HashMap`, which is not suitable for real-world applications. In practice, more secure methods like database storage and encryption should be used.

### Disclaimer

This application is for educational purposes only. Do not use it for real banking transactions.
