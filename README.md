# Bank-Management-System2
A simple CLI Bank Management System built in C++ that features Client CRUD operations, Transaction management, and a multi-user Login system with custom permissions.

# Bank Management System 2

A simple CLI Bank Management System built in C++ that features Client CRUD operations, Transaction management, and a multi-user Login system with custom permissions.

## 🚀 Features

- **Multi-User Login System:** Secure access requiring a username and password.
- **Role-Based Permissions:** Custom user access levels (e.g., full access or limited view/transaction rights).
- **Client Management (CRUD):** - List all clients.
  - Add new clients.
  - Delete/Update client details.
  - Find a specific client.
- **Transaction Management:**
  - Deposit funds.
  - Withdraw funds (with balance validation).
  - View total balances of all accounts.
- **User Management:** Admin capability to add, delete, update, and list system users.
- **Persistent Storage:** Data is stored and updated locally in plain text files (`Clients.txt` and `Users.txt`).

## 🛠️ Built With

- **C++** (Standard Library, fstream, vector, iomanip)
