# Exp-1: ATM & Banking System

## AIM
To study, design, and understand the working of an **ATM & Banking System** using UML concepts by identifying the actors, use cases, and functionalities involved in the system.


## SOFTWARE REQUIREMENTS SPECIFICATION (SRS)

### 1. Introduction
The **ATM & Banking System** is a software model that automates various banking operations such as cash withdrawal, deposit, balance inquiry, and fund transfer. The system ensures secure interaction between the user and the bank through an ATM interface, reducing the need for manual intervention.

### 2. Purpose
The main purpose of this project is to simulate how an ATM interacts with a bank’s backend server to provide banking services to customers securely and efficiently.

### 3. Scope
This system covers:
- Basic banking operations (withdrawal, deposit, balance check, fund transfer)
- User authentication through PIN verification
- Real-time communication between the ATM and the bank server
- Maintenance operations like cash loading and diagnostics

---

### 4. Functional Requirements
- **Card Insertion:** The user initiates the process by inserting a valid ATM card.  
- **PIN Verification:** The ATM validates the user’s identity through a secure PIN.  
- **Cash Withdrawal:** The user can withdraw a specific amount if the account has sufficient balance.  
- **Cash Deposit:** The user can deposit money into their bank account.  
- **Balance Inquiry:** Displays the current account balance.  
- **Fund Transfer:** Allows transferring funds between two accounts.  
- **Maintenance Operations:** The maintenance staff can load cash or perform system checks.

---

### 5. Non-Functional Requirements
- **Security:** Data encryption and PIN protection are mandatory for all transactions.  
- **Reliability:** The system should handle all transactions without data loss or errors.  
- **Performance:** All user requests should be processed quickly and efficiently.  
- **Availability:** The ATM must be available 24/7.  
- **Usability:** Interface should be simple and user-friendly.  

---

### 6. System Actors
- **Customer:** Performs regular banking operations using the ATM.  
- **Bank Server:** Handles transaction processing, authentication, and account updates.  
- **Maintenance Staff:** Responsible for refilling cash and maintaining the ATM hardware/software.  

---

### 7. Use Cases
The main use cases of the system include:
1. Insert Card  
2. Enter PIN  
3. Withdraw Cash  
4. Deposit Cash  
5. Check Balance  
6. Transfer Funds  
7. Load Cash (Maintenance)  
8. Perform Maintenance  

Each use case defines how an actor interacts with the system to complete a specific task.

---


# DIAGRAMS:

## Use Case:
![505839391-721e1d32-e532-4c2c-b726-c01478ad8735](https://github.com/user-attachments/assets/8a13015f-cea6-4bdb-9b57-889a2be08e99)


## Class Diagram:
![ClassDiagram1](https://github.com/user-attachments/assets/aec98941-5168-4e74-95d7-07658d428456)


## Sequence Diagram:
![SequenceDiagram1](https://github.com/user-attachments/assets/efd3ba2f-192e-4d2e-831e-dfd87966917a)


## Communication Diagram:
<img width="926" height="801" alt="image" src="https://github.com/user-attachments/assets/f92079bc-5342-4d93-a626-1fec672bf31a" />


## Activity Diagram:
![444970820-cd1fb4b0-b3ff-4817-9916-b5e6cec8e001](https://github.com/user-attachments/assets/e587cb4a-a931-44d0-933b-9e22165eb1b9)


## Package Diagram:
![444970870-43ee4525-5d37-4377-a0c8-eb824d97d417](https://github.com/user-attachments/assets/a650424e-f02f-43ce-ac70-03b4f14ab514)


# RESULT:

The **ATM & Banking System** effectively demonstrates how users can securely access banking services through an automated interface. It highlights the core functionality, actor roles, and interactions that occur during banking transactions. This model serves as a foundation for understanding how real-world ATM systems are designed and implemented using software engineering principles.
