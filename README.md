Purpose: This project is a simple command-line banking application designed to allow users to create accounts, deposit and withdraw money, check account balances, and transfer funds 
between accounts. The primary focus of this project is on data security, input validation, and basic user authentication. Additionally, the system includes features that allow users to 
exit or go back from any state, improving user experience.

Key Features
1. User Account Management: 
• Users can create an account with a unique username, password, and account number. 
• Secure login functionality is implemented with password hashing and account lockout mechanisms.
2. Basic Banking Operations: 
• Deposit: Users can deposit money into their account. 
• Withdraw: Users can withdraw money, ensuring they do not overdraw their account. 
• Balance Check: Users can check their current balance. 
• Transfer: Users can transfer money between accounts.
3. Data Security:
• Passwords are securely stored using hashing (SHA-256).
• All sensitive information is handled securely and not stored in plain text.
4. Data Storage:
• A simple file-based storage (JSON) is used to store user account information and transaction history.
5. Transaction Logging:
• All transactions (deposits, withdrawals, transfers) are logged with timestamps to maintain a clear record.
6. Enhanced User Navigation:
• Users can exit or go back from any state, improving the usability and flexibility of the system
