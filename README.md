Banking System
==============

Welcome to the AYUSH BANK repository. This project simulates an ATM and bank account management system using Java Swing and MySQL. The application provides a user-friendly interface for banking operations.

Features
--------

1.  **Login Page**
    
    *   Card Number input.
        
    *   PIN input.
        
    *   Options to Sign In, Clear, or Sign Up.
        
2.  **Application Form**
    
    *   Three pages for detailed user data collection:
        
        *   **Page 1: Personal Details**
            
            *   Fields: Name, Father's Name, Gender, Date of Birth, Email Address, Marital Status, Address, City, Pin Code, State.
                
            *   Gender options: Male, Female, Other.
                
        *   **Page 2: Additional Details**
            
            *   Fields: Religion, Category, Income, Educational Qualification, Occupation, PAN Number, Aadhar Number.
                
            *   Options for Senior Citizen and Existing Account: Yes/No.
                
        *   **Page 3: Account Details**
            
            *   Account Types: Saving Account, Current Account, Fixed Deposit Account, Recurring Deposit Account.
                
            *   Fields: Card Number (16 digits), PIN (4-digit password).
                
            *   Services Required: ATM Card, Mobile Banking, Cheque Book, Internet Banking, Email Alerts, E-Statement.
                
3.  **ATM Transaction Page**
    
    *   Options for transactions:
        
        *   Deposit
            
        *   Fast Cash
            
        *   PIN Change
            
        *   Cash Withdrawal
            
        *   Mini Statement
            
        *   Balance Enquiry
            
        *   Exit
            

Technologies Used
-----------------

*   **Frontend**: Java Swing (JFrame for GUI).
    
*   **Backend**: MySQL for database management.
    

How to Run
----------

1.  Clone this repository.
    
2.  Import the project into your preferred IDE (e.g., IntelliJ IDEA, Eclipse).
    
3.  Configure the MySQL database with the provided schema and credentials.
    
4.  Run the Main class to start the application.
    

Database Schema
---------------

*   **User Table**: Stores personal and account details.
    
*   **Transaction Table**: Logs all transactions for each user.
    
*   **Authentication Table**: Handles login credentials (Card Number and PIN).
    

Screenshots
-----------

**Developer:** Ayush Rajendra Raut
